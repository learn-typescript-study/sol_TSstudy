### 색션9: es6문법

##### 구조분해 문법
- 변수 선언 형식이 아래와 같이 자유로워지는 것을 의미
```javascript
const {a,b,c} = obj
const {a: "하고싶은별칭",b,c} = obj2
```

##### Async & Await 
- 비동기는 해당 줄이 처리 되기전까지 잠시 멈춘다. => 그래서 콜백처리 => 단점이 잇음 그래서 어싱크 어웨이트 사용 =>
동기적 (절자척)으로 코드를 작성을 도와줌


### 색션10: TS에서 strict 옵션
- strict 옵션을 true로 하면 관련 strict 옵션들을 다 킨것
// 타입스크트
-// deathsList이 null이 아니다,  non-null assertiob
         deathsList!.appendChild(li);

