리액트 컴포넌트
https://ko.reactjs.org/docs/react-dom.html

JSX 주의사항
- class -> className로 사용
- for -> htmlFor로 사용

- 소문자가 아닌 카멜케이스로 작성
onClick={activatelasers} (x)
onClick={activateLasers} (o)

- 문자열이아닌 함수로 전달
onClick="함수이름()" (x) 
onClick={함수이름} (o)

https://dev-pengun.tistory.com/entry/React-%EB%A6%AC%EC%95%A1%ED%8A%B8-%EA%B8%B0%EC%B4%88-%EB%B0%B0%EC%9A%B0%EA%B8%B0-5-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EC%B2%98%EB%A6%AC%ED%95%98%EA%B8%B0