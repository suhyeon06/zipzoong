# 🖥️ ZipZoong

> 데스크 셋업이란, 개인의 작업 공간을 최적화하기 위해 키보드, 마우스, 모니터 등의 주변기기와 함께 책상 주변을 구성하는 방법을 말합니다.
>
> 우리의 서비스는 각 개인의 취향과 요구에 맞춰 키보드, 마우스, 모니터 등의 주변기기를 선별하여 추천해줍니다.
>
>단순히 제품을 추천하는 것을 넘어, 사용자의 선호도, 작업 환경, 예산 등 다양한 요소를 고려하여 개인 맞춤형 데스크 셋업을 제안합니다. 
>
>당신만의 이상적인 작업 공간을 구성해보세요. 여러분의 취향을 완벽히 이해하고, 최상의 사용 경험을 제공하기 위해 끊임없이 노력하겠습니다.

### 프로젝트 기간

-   기획 및 설계 :  2024.02.26 - 2024.03.08
-   프로젝트 개발 : 2024.03.11 - 2024.04.05

### 구성원

-   백엔드 3명
-   프론트엔드 2명
-   데이터 1명

<br/>

## 🔨 주요 기술 스택

### 🗺️ Frontend
-   `Node`
-   `Next`
-   `React`
-   `TypeScript`

### 📮 Backend
-   `Java`
-   `Spring Boot`
-   `Spring Security`
-   `Spring Data JPA`
-   `JWT`
-   `Gradle`

### 📰 Data
-   `Python`

### 🧮 DB
-   `MySQL`
-   `Redis`

### 🌏 Deploy

-   `AWS EC2`
-   `Docker`
-   `Docker-compose`
-   `Nginx`
-   `Jenkins`

### 📞 Communication

-   형상 관리 - `Gitlab`,`Sourcetree`
-   이슈 및 스크럼 관리 - `Jira`
-   의사소통, 협업 - `Notion`, `Mattermost`
-   디자인 - `Figma`
  
<br>

## **📚 목차**  

1️⃣ [타겟층](#-타겟층)   
2️⃣ [주요 기능](#-주요-기능)  
3️⃣ [서비스](#-서비스)  
4️⃣ [실행방법](#-실행방법)  
5️⃣ [팀 구성](#-팀-구성)  
6️⃣ [기술 아키텍쳐](#-기술-아키텍쳐)  
7️⃣ [ERD 다이어그램](#-erd-다이어그램)  
8️⃣ [API 명세서](#-api-명세서)   
9️⃣ [와이어프레임](#-와이어프레임)  
1️⃣0️⃣ [DATA 상세](#-data-상세)

<br>

## 😮 타겟층
    ✔ 데스크 셋업을 구성하고자 하는 사람들
    ✔ 어떤 제품을 사용해야할지 고민하는 사람들
   
<br>

## 👍 주요 기능
|구분|기능|설명|비고|
|:---|:---|:---|:---|
|1|소셜 로그인| - Google 로그인을 통해 로그인할 수 있다.<br> - Naver 로그인을 통해 로그인할 수 있다. <br> - Kakao 로그인을 통해 로그인할 수 있다.||
|2|설문 기반 추천| - 설문을 기반으로 개인의 선호도에 따른 제품 조합을 추천받을 수 있다. ||
|3|유사 제품 추천| - 제품을 기반으로 유사한 제품을 추천 받을 수 있다. ||
|4|조합 공유| - 자신이 추천 받은 조합을 공유할 수 있다. ||
|5|관심 조합| - 추천받은 데스크 셋업을 저장할 수 있다.||
|6|관심 제품| - 관심있는 제품을 저장할 수 있다.||
<br>

# 서비스
## 📌 소셜 로그인

 - Google / Kakao 를 통해 로그인할 수 있다.

 <img width="800" src="assets/images/소셜로그인.png"> <br>

<br>
<br>
      
## 📌 - 설문 기반 추천

 - 설문을 기반으로 개인의 선호도에 따른 제품 조합을 추천받을 수 있다.

 <img width="800" src="assets/images/설문기반추천.gif"> <br>


<br>
<br>
   

## 📌 - 설문 기반 추천 상세

 - 제품 조합 상세를 확인할 수 있다.
   
 <img width="800" src="assets/images/설문기반추천상세.gif"> <br>


<br>
<br> 

  

## 📌 - 최저가 사이트 연동
 - 자신이 추천 받은 조합 제품의 최저가 사이트로 접속할 수 있다.
 
 <img width="800" src="assets/images/설문기반추천.gif"> <br>

<br>
<br> 
  


## 📌 - 관심 조합 및 제품
 - 추천받은 데스크 셋업의 조합 및 제품을 저장할 수 있다.

 <img width="800" src="assets/images/관심조합및제품.gif"> <br>

  
<br>
<br>  
     
  
## 📌 - 게시판
 - 게시판에 게시글을 작성할 수 있고 글 내부에 추천받은 조합을 추가할 수 있다. 
    
 <img width="800" src="assets/images/게시판.gif"> <br>

  
<br>
<br>  
  

## 💾 실행방법

### [🔗 포팅 메뉴얼 바로가기](https://lab.ssafy.com/s10-bigdata-recom-sub2/S10P22A204/-/tree/master/exec?ref_type=heads)
- exec 폴더 내 포팅 메뉴얼 참조


<br>

## 👬 팀 구성
<table>
  <tbody>
    <tr>
     <td align="center">
        <a href="">
            <img width="150" src="assets/members/수안.png"> <br>
            <sub><b>유수안</b></sub>
        </a>
        <br />
        <div>팀장, INFRA, BE</div>
      </td>
      <br/>
      <td align="center">
        <a href="">
            <img width="150" src="assets/members/지은.png"> <br>
            <sub><b>홍지은</b></sub>
        </a>
        <br />
        <div>FE</div>
      </td>
      <br/>
      <td align="center">
        <a href="https://github.com/zsa332">
            <img width="150" src="assets/members/성원.png"> <br>
            <sub><b>서성원</b></sub>
        </a>
        <br />
        <div>BE, DATA</div>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="">
          <img width="150" src="assets/members/진희.png"> <br>
          <sub><b>장진희</b></sub>
          </a>
          <br />
          <div>DATA</div>
      </td>
      <td align="center">
        <a href="">
            <img width="150" src="assets/members/현정.png"> <br>
            <sub><b>유현정</b></sub>
        </a>
        <br />
        <div>FE</div>
      </td>
      <td align="center">
        <a href="">
            <img width="150" src="assets/members/수현.png"> <br>
            <sub><b>이수현</b></sub>
        </a>
        <br />
        <div>BE</div>
      </td>
    </tr>
  </tbody>
</table>

<br>

## ⚙ 기술 아키텍쳐
<img width="800" src="assets/아키텍쳐설계.png"> <br>

<br>

## 💎 [ERD 다이어그램](https://www.erdcloud.com/d/LhpmjPdjFc5gMy5iW)
<img width="800" src="assets/ERD다이어그램.png"> <br>

<br>

## 📘 [API 명세서](https://yoosue.notion.site/API-1ef45e4a2dd046eaba08050ea33b8faa?pvs=4)
<img width="800" src="assets/API명세1.png"> <br>

<img width="800" src="assets/API명세2.png"> <br>

<br>

## 🍏 [와이어프레임](https://www.figma.com/file/OQA4g8cBEGpWA8tUEUbaOu/Figma?type=design&mode=design&t=VRuVakN1jpVacYo4-1)
<img width="800" src="assets/와이어프레임.png"> <br>



## 📊 [DATA 상세]() 

#### 1. 실제 설문 조사 결과

1. 제품 비중
    1. 모니터 - 키보드 - 마우스
2. 데스크 셋업 예산 범위
    1. 50만원 이하
    2. 100만원  이하
    3. 30만원 이하
3. 모니터 선택 시 가장 중요한 점
    1. 기능
    2. 크기
    3. 가격
    4. 디자인
4. 키보드 선택 시 중요한 점
    1. 타건감
    2. 디자인
    3. 가격
    4. 소음
    5. 키압
    6. 유/무선
5. 마우스 선택 시 가장 중요한 점
    1. 유/무선
    2. 가격
    3. 디자인
    4. 소음
    5. 손목이 편한 (버티컬)

→ 이 결과를 바탕으로 변수를 설정하여 데이터 수집

#### 2. 데이터 수집

모니터, 키보드, 마우스 별 다나와 사이트 내 데이터 크롤링 및 전처리

- selenium : 웹 페이지 자동화 및 테스트를 위한 프레임워크
- Beautiful Soup : Selenium 웹 드라이버를 관리하기 위한 라이브러리
- pandas : 데이터 조작 및 분석을 위한 라이브러리
- Regular Expression : 문자열을 처리하고 검색하기 위한 정규 표현식을 지원하는 라이브러리

등 사용

모니터 변수

| 상품명 | 제조사 | 구매링크 | 이미지 | 가격 | 크기 | 비율 | 패널형태 | 패널종류 | 주사율 | 해상도 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

키보드 변수

| 상품명 | 제조사 | 구매링크 | 이미지 | 가격 | 연결 방식 | 연결 인터페이스 | 접점 방식 | 키 배열 | 키압 | 키보드 형태 | LED 유무 | 키보드 축 | 키보드 색상 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

마우스 변수

| 상품명 | 제조사 | 구매링크 | 이미지 | 가격 | 종류 | 연결 방식 | 연결 인터페이스 | dpi | 가로길이 | 세로길이 | 높이 | 무게 | 색상 | 소음 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

#### 3. 설문 - 데이터 전처리

- 가격
    - 총 가격대(10) : 최대 500만원
    - 모니터 가격(6)
    - 키보드 가격(3)
    - 마우스 가격(1)
- 간단/자세
    - 사용자 편의를 위해 간단하게 설문 조사를 실시하는 경우와 자세하게 설문조사를 하는 경우로 나눠서 진행
- 용도
    - 사무, 게이밍, 개발, 영상, 취미 (중복 선택 가능) )
    - ai 및 전문가 리뷰를 참고하여 구분 기준을 세우고 각 용도에 맞게 모니터, 키보드, 마우스 제품을 임의로 나눔
    - 모니터 용도
    - 키보드 용도
    - 마우스 용도
- 색상
    - 블랙톤, 화이트톤, 컬러톤, 상관없음
    - 키보드 색상
    - 마우스 색상
- 연결 방식
    - 키보드 유/무선
    - 마우스 유/무선
- 소음 유/무
    - 키보드
    - 마우스
- 각 제품별 특화 질문
    - 모니터
        - 사이즈, 비율, 패널 형태
    - 키보드
        - 키배열, 종류
- 손목 건강에 따른 키보드, 마우스 제품 추천
    - 키보드 : 키압이 낮거나 인체공학 키보드
    - 마우스 : 버티컬 마우스

→ 설문 결과를 DB에 저장

#### 4. 설문 기반 추천 알고리즘

저장된 설문 결과를 제품별로 나누고, 기존의 DB에 저장되어 있는 제품별로 컬럼을 맞춰 코사인 유사도 계산을 바탕으로 콘텐츠 기반 필터링

- 원핫 인코딩 : 각 범주를 별도의 열로 변환하여, 모델이 각 범주의 존재 여부를 명확하게 구분할 수 있게 함.
    - 각 범주를 새로운 이진 변수로 변환하여 해당하는 변수에만 1을 할당하고, 나머지는 0으로 채움.
    - 순서가 없는 변수
    - 모니터 : 용도, 패널형태, 패널타입, 비율, 크기
    - 키보드 : 용도, 색상, 키보드 연결 방식, 키보드 종류
    - 마우스 : 용도, 색상, 마우스 연결 방식
- 라벨 인코딩 : 각 범주형 변수에 숫자를 할당하여 범주를 나타냄.
    - 순서가 있는 변수. 범주 간에 대소관계가 있을 때 사용.
    - 키보드 : 축(소음 정도), 키 배열
- 유사도 계산
    - 가격 유사도 계산 : 가격 절대값 차이의 역수로 계산 (비슷할수록 유사도가 높아짐)
    - 가격 특성 외의 유사도 계산
        - 가격 제외 공통 컬럼 선택 후 표준화
            - 표준화 : 데이터의 평균을 0으로 만들고, 표준 편차를 1로 만들어 데이터를 정규 분포에 맞게 조정하는 작업. 각 특성의 척도를 조정하여 데이터를 비교하거나 모델링하기 쉽게 만들어줌.
        - 코사인 유사도 계산
            - 코사인 유사도 : 두 벡터 간의 유사성을 측정. 두 벡터 간의 각도를 기반으로, 벡터의 방향에 따라 달라짐. 두 벡터가 얼마나 ‘비슷한’ 방향을 가지는지 측정하는 지표
    - 가격 유사도 * 가격 비중 + 가격 외의 코사인 유사도 * (1-가격 비중)
- 콘텐츠 기반 필터링 : 주어진 아이템의 콘텐츠나 속성을 기반으로 유사한 아이템을 추천하거나 필터링하는 방법

#### 5. 유사 상품 추천 알고리즘

설문 기반 추천 알고리즘과 동일

기존의 DB에 저장되어 있는 제품별로 코사인 유사도 계산을 바탕으로 콘텐츠 기반 필터링

- 원핫 인코딩 : 각 범주를 별도의 열로 변환하여, 모델이 각 범주의 존재 여부를 명확하게 구분할 수 있게 함.
    - 각 범주를 새로운 이진 변수로 변환하여 해당하는 변수에만 1을 할당하고, 나머지는 0으로 채움.
    - 순서가 없는 변수
    - 모니터 : 용도, 패널형태, 패널타입, 비율, 크기
    - 키보드 : 용도, 색상, 키보드 연결 방식, 키보드 종류
    - 마우스 : 용도, 색상, 마우스 연결 방식
- 라벨 인코딩 : 각 범주형 변수에 숫자를 할당하여 범주를 나타냄.
    - 순서가 있는 변수. 범주 간에 대소관계가 있을 때 사용.
    - 키보드 : 축(소음 정도), 키 배열
- 유사도 계산
    - 가격 유사도 계산 : 가격 절대값 차이의 역수로 계산 (비슷할수록 유사도가 높아짐)
    - 가격 특성 외의 유사도 계산
        - 가격 제외 공통 컬럼 선택 후 표준화
            - 표준화 : 데이터의 평균을 0으로 만들고, 표준 편차를 1로 만들어 데이터를 정규 분포에 맞게 조정하는 작업. 각 특성의 척도를 조정하여 데이터를 비교하거나 모델링하기 쉽게 만들어줌.
        - 코사인 유사도 계산
            - 코사인 유사도 : 두 벡터 간의 유사성을 측정. 두 벡터 간의 각도를 기반으로, 벡터의 방향에 따라 달라짐. 두 벡터가 얼마나 ‘비슷한’ 방향을 가지는지 측정하는 지표
    - 가격 유사도 * 가격 비중 + 가격 외의 코사인 유사도 * (1-가격 비중)
- 콘텐츠 기반 추천 알고리즘 : 주어진 아이템의 콘텐츠나 속성을 기반으로 유사한 아이템을 추천하거나 필터링하는 방법
