# IL

### TS

<details>
  <summary>
  TS 주요 문법
</summary>

## 타입 명시

```ts
let 변수이름 : 데이터타입 = 할당할 값

let x : string = 'kim'
```
<details>
  <summary>
  데이터 타입 종류
</summary>

- 기본 데이터 타입

  - number . string , boolean
  - null : 의도적으로 값이 없음
  - undefined : 값이 할당 되지 않음
    
- 객체 타입

  - object
  - array
  - tuple

- 특수 타입

  - any
  - unknown : 타입을 미리 알 수 없는 경우

</details>

### 인터페이스

타입을 타입스크립트에게 설명해주기 위한 용도

```ts
interface Info{
 name : string;
 age : number;
 job : boolean;
}

// 상속 받는 것도 가능
class MyInfo implements Info {
  name = 'kim';
  age = 20;
  job = false;
}
```

</details>
