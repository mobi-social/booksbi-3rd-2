## 값 이란?

= 식이 평가되어 생성된결과

- 모든값은 데이터 타입을 가지며 메모리에 2진수 , 즉 비트의 나열로 저장된다.
- 변수는 하나의 값을 저장하기 위해 확보한 메모리 공간 자체 또는 그 메모리 공간을 식별하기 위해 붙인 이름.
- 변수에 할당 되는것 = **값**
- 값은 다양한 방법으로 생성될 수 있으며, 식 뿐만 아니라 가장 기본적인 방법인 리터럴을 사용할 수 있음.

## 리터럴 이란?

= 사람이 이해할 수 있는 문자 또는 약속된 기호를 사용해 값을 생성하는 표기법

- 자바스크립트 엔진은 코드가 실행되는 시점인 런타임에 리터럴을 평가해 생성함.

## **표현식 이란?**

= 값으로 평가될 수 있는 문

- 표현식이 평가되면 새로운 값을 생성하거나 기존 값을 참조함.

```jsx
var score = 100;
```

- 값으로 평가될 수 있는 문은 모두 표현식
- 동치 : 표현식과 표현식이 평가된 값, 동등한 관계

## 문 이란?

= 프로그램을 구성하는기본 단위이자 최소 실행 단위

- 문은 여러 **토큰** (문법적인 의미를 가지며 문법적으로 더이상 나눌 . 수없는 코드의 기본 요소) 으로 구성됨
- 키워드, 식별자, 연산자, 리터럴, 세미클론, 마침표 등의 특수 기호로 구분함.

## 표현식 문 VS 표현식이 아닌 문

- 구분하는가장 간단하고 명료한 방법은 변수에 할당하는것
- 표현식은 문의 일부일 수도 있고 그자체로 문이 될 수 있음
- 표현식인 문
    
    = 값으로 평가될수있음
    
    = 변수에 할당 할 수있음
    
- 표현식이아닌문
    
    = 값으로 평가될 수 없음
    
    = 변수에 할당 불가능