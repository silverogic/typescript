typescript는 compiled language 입니다.
- 컴파일/컴파일러가 필요
- 컴파일된 결과물을 실행
- *컴파일 : 프로그래밍 언어를 기계가 실행 가능한 기계어로 번역하는 과정

그러나 typescript의 컴파일은 조금 다릅니다.

typescript는 1차 컴파일에는 고급언어-고급언어의 변환을 하는 거고, 2차 컴파일시 런타임시에 javascript 엔진으로 고급언어-기계어 변환을 합니다.

```
[1단계: 컴파일/트랜스파일]
TypeScript (.ts) ──(tsc 컴파일러)──> JavaScript (.js)

[2단계: 런타임 실행]
JavaScript (.js) ──(V8 엔진 / JIT 컴파일)──> 기계어 (010101...) ──> CPU 실행
```