## React code split
- 웹서비스가 배포되어 질 때 모든 코드들은 번들링이 된다 (하나의 코드로 묶인다) 
- 프로젝트의 데이터 양이 크면 성능적 문제가 발생한다. 
- 보통 유저가 당장 필요한 정보에 우선 순위를 두어 순서대로 로딩 하는 방법이있다 (유저에게 티내지 않는다)
- 번들이 거대해지는 것을 방지하기 위해 번들은 나눈다 ,Webpack, Rollup, Browserify 번들러 지원 기능

## React 구현 방법, 어떻게 적용했는지
 - 바벨: ES6를 ES5로 바꿔주는 모듈 번들러
 - 웹팩: 자원들을 하나의 파일로 병합 및 압축 해주는 모듈 번들러

## 함수형 컴포넌트
- JSX 를 Return문을 사용해서 반환
- state를 사용할 수 없다.
- 생명주기 함수를 작성할 수 없다.
  
## 클래스형 컴포넌트
- class 키워드로 시작
- component 로 상속 받음
- render() 함수를 사용해서 JSX 반환
- props 조회할 때 this 키워드 사용
- 라이프 사이클 : 마운트 / 업데이트/ 언마운트
- 상태값을 가질 수 있고, 생명주기 함수를 작성할 수 있다.

## Restful Service
	- HTTP URL을 통해 자원을 명시하고 HTTP Method (POST, GET, PUT, DELETE)를 통해 해당 자원에 대한 CRUD를 적용하는 것
	- Client에서 바로 객체로 치환 가능한 형태의 데이터 통신 / 클라이언트와 서버를 연결해주는 개념
￼
## 상태관리 라이브러리 사용했는지
 1) 리덕스 - 하나의 store에서 객체를 가져다 쓴다 (복잡함)
 2) context api - state가 변경되지 않은 부분도 리렌더링이 일어난다
 3) recoil - stater가 변경된 곳만 리렌더링이 일어난다
 
## jwt 왜 사용했는지
사용자 정보 보안

## session 어떻게 저장했는지 
localstorege에 넣었다.

## 쿠키와 localstorege의 차이

## 프로젝트 UI 화면 왜 그렇게 설계했는지

## 왜 MUI 사용했는지

## hash 라우터 왜 사용했는지

## webpack babel 에서 target 이 뭔지 

## var, let, const
