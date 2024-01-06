<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>회원가입</title>
    <link rel="stylesheet" href="회원가입.css" />
  </head>
  <body>
    <br />
    <h1 class="title">JOIN US</h1>
    <br />
    <hr />
    <br />

    <table border="1">
      <caption>
        <strong class="join_infor">&nbsp;가입정보 </strong>
      </caption>
      <br />
      <tbody>
        <tr>
          <th>아이디</th>
          <td>
            <div>
              <input
                id="ID"
                name="ID"
                placeholder
                value
                type="text"
                maxlength="16"
              />

              &nbsp;&nbsp;영문 대소문자/숫자 4~16자
            </div>
          </td>
        </tr>

        <tr>
          <th>비밀번호</th>
          <td>
            <div>
              <input
                id="pswd1"
                name="PW"
                placeholder
                value
                type="text"
                maxlength="20"
              />
              &nbsp;&nbsp;영문 대소문자/숫자/특수문자 중
              <strong>3가지</strong> 이상 조합, 8자~20자
            </div>
          </td>
        </tr>

        <tr>
          <th>비밀번호 확인</th>
          <td>
            <input
              id="pswd2"
              name="Pw_check"
              placeholder
              value
              type="text"
              maxlength="20"
            />
          </td>
        </tr>

        <tr>
          <th>이름</th>
          <td>
            <input id="name" name="name" placeholder value type="text" />
          </td>
        </tr>

        <tr>
          <th>휴대폰번호</th>
          <td>
            <input
              id="phone_number1"
              name="phone_number"
              placeholder
              value
              type="text"
              maxlength="3"
            />
            -
            <input
              id="phone_number2"
              name="phone_number"
              placeholder
              value
              type="text"
              maxlength="4"
            />
            -
            <input
              id="phone_number3"
              name="phone_number"
              placeholder
              value
              type="text"
              maxlength="4"
            />
          </td>
        </tr>

        <tr>
          <th>생년월일</th>
          <td>
            <div>
              <input
                id="birth"
                name="birth"
                placeholder
                value
                type="text"
                maxlength="4"
                width="30px"
              />
              년
              <input
                id="birth"
                name="birth"
                placeholder
                value
                type="text"
                maxlength="2"
              />
              월
              <input
                id="birth"
                name="birth"
                placeholder
                value
                type="text"
                maxlength="2"
              />
              일
            </div>
          </td>
        </tr>

        <tr>
          <th>이메일</th>
          <td>
            <input
              id="email"
              name="email"
              placeholder
              value
              type="text"
              aria-placeholder=""
            />
          </td>
        </tr>
      </tbody>
    </table>
    <br /><br />
    <div id="agree">
      <p><strong>전체동의</strong></p>
      <input type="checkbox" id="all_agree" /> 이용약관 및 개인정보수집 및 이용,
      쇼핑정보 수신(선택)에 모두 동의합니다.<br />
      <br />
      <br />
      <p><strong>[필수] 이용약관 동의</strong></p>
      <br />

      <textarea cols="100%" rows="10%">
제1조(목적)
이 약관은 HPEMALL(전자상거래 사업자)가 운영하는 HPEMALL 사이버 몰(이하 “몰”이라 한다)에서 제공하는 인터넷 관련 서비스(이하 “서비스”라 한다)를 이용함에 있어 사이버 몰과 이용자의 권리․의무 및 책임사항을 규정함을 목적으로 합니다.
※「PC통신, 무선 등을 이용하는 전자상거래에 대해서도 그 성질에 반하지 않는 한 이 약관을 준용합니다.」
      
제2조(정의)
① “몰”이란 HPEMALL이 재화 또는 용역(이하 “재화 등”이라 함)을 이용자에게 제공하기 위하여 컴퓨터 등 정보통신설비를 이용하여 재화 등을 거래할 수 있도록 설정한 가상의 영업장을 말하며, 아울러 사이버몰을 운영하는 사업자의 의미로도 사용합니다.
② “이용자”란 “몰”에 접속하여 이 약관에 따라 “몰”이 제공하는 서비스를 받는 회원 및 비회원을 말합니다.
③ ‘회원’이라 함은 “몰”에 (삭제) 회원등록을 한 자로서, 계속적으로 “몰”이 제공하는 서비스를 이용할 수 있는 자를 말합니다.
④ ‘비회원’이라 함은 회원에 가입하지 않고 “몰”이 제공하는 서비스를 이용하는 자를 말합니다.</textarea
      >
      <br />이용약관에 동의하십니까?&nbsp;&nbsp;<input
        type="checkbox"
        id="yes_agree"
      />동의함 <br /><br /><br />
      <p><strong>[필수] 개인정보 수집 및 이용 동의</strong></p>
      <br />

      <textarea cols="100%" rows="10%">
1. 개인정보 수집목적 및 이용목적
가. 서비스 제공에 관한 계약 이행 및 서비스 제공에 따른 요금정산
콘텐츠 제공 , 구매 및 요금 결제 , 물품배송 또는 청구지 등 발송 , 금융거래 본인 인증 및 금융 서비스
        
나. 회원 관리
회원제 서비스 이용에 따른 본인확인 , 개인 식별 , 불량회원의 부정 이용 방지와 비인가 사용 방지 , 가입 의사 확인 , 연령확인 , 만14세 미만 아동 개인정보 수집 시 법정 대리인 동의여부 확인, 불만처리 등 민원처리 , 고지사항 전달

2. 수집하는 개인정보 항목 : 이름 , 생년월일 , 성별 , 로그인ID , 비밀번호 , 자택 전화번호 , 휴대전화번호 , 이메일 , 14세미만 가입자의 경우 법정대리인의 정보
        
3. 개인정보의 보유기간 및 이용기간
원칙적으로, 개인정보 수집 및 이용목적이 달성된 후에는 해당 정보를 지체 없이 파기합니다. 단, 다음의 정보에 대해서는 아래의 이유로 명시한 기간 동안 보존합니다.
        </textarea
      >
      <br />이용약관에 동의하십니까?&nbsp;&nbsp;<input
        type="checkbox"
        id="yes_agree"
      />동의함
    </div>
    <br /><br /><br /><br /><br />
    <div class="join_bt">
      <button type="button" id="join_bt">
        <span>가입하기</span>
      </button>
    </div>
  </body>
</html>
<!--CSS-->
* {
  margin: 0px;
  box-sizing: border-box;
}
html {
  display: flex;
  justify-content: center;
}
body {
  background-color: rgb(240, 240, 240);
}

h1 {
  text-align: center;
  font-size: 30px;
}

table {
  width: 680px;
  height: 300px;
}
table,
tr,
th {
  border: 1px solid rgb(240, 240, 240);
  border-collapse: collapse;
  font-family: Dotum, "돋움", Helvetica, sans-serif;
  font-size: 12px;
}

caption {
  text-align: left;
}

th {
  padding: 5px;
  padding-top: 20px;
  padding-bottom: 20px;
  text-align: left;
  width: 20%;
}

input {
  border: 10px;
  border-color: rgb(240, 240, 240);
}

td {
  padding-left: 5px;
}

#join_bt {
  background-color: rgb(0, 0, 50);
  display: block;
  height: 40px;
  width: 100%;
  border: solid 1px rgb(0, 0, 50);
  box-sizing: border-box;
  padding-top: 4px;
  font-size: 16px;
  color: white;
  cursor: pointer;
  margin-bottom: 20px;
}

#phone_number1 {
  width: 65px;
}

#phone_number2 {
  width: 65px;
}

#phone_number3 {
  width: 65px;
}

#birth {
  width: 65px;
}

#id {
  font-size: 12px;
}

#agree {
  font-size: 14px;
}
