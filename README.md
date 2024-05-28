# 수업 내용 필기

수업내용 필기를 위한 마크다운(markdown)을 작성하는 방법

## 랜덤(Random)  - 두번째 제목  
랜덤은 예측 불가능한 값을 말합니다.  
랜덤을 만드는 방법은 여러가지가 있습니다.  

1. Random이라는 도구를 생성하는법
2. Math.random() 명령을 사용하는법
3. SecureRandom 도구를 생성하여 사용

여기서는 Random 도구를 생성합니다.
```java
Random r = new Random();
```
  
이 도구를 사용하기 위해서는 import가 필요합니다.
  
```java
import java.util.Random;
```
  
import는 직접 작성하지 않고 **단축키**인 `ctrl + shift + O`를 사용하여 가능합니다.

## 랜덤 정수 추첨

생성한 도구를 이용해서 랜덤한 정수를 추첨 할 수 있습니다.
단, 생성을 위해서는 범위를 정해야 합니다.

- 사람은 범위를 이야기 할 때 `a`부터 `b`까지 라고 합니다.
- 자바는 범위를 이야기 할 때 `a`부터 `b`개 라고 합니다.

주요 랜덤 값들의 범위는 다음과 같이 표현 될 수 있습니다.
|항목|범위|
|:---:|---|
|주사위|`1`부터 `6`개|
|로또|`1`부터 `45`개|
|두자리 정수| `10`부터 `90`개|

난수 생성의 원리가 궁금하면 [위키백과](https://ko.wikipedia.org/wiki/%EB%82%9C%EC%88%98)에서 확인 할 수 있습니다.

![카지노 이미지](https://i.namu.wiki/i/Tu93EDNTHxVfDsDjQEoYRQQnkNmZe1ySr70TpkyxU3kd0IoWS96oLBhl3kbl6EIKS-dXVCBkjLK4Ga1pLtZ92w.webp)
