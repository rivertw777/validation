# 검증
## 검증 요구사항
+ 타입 검증
  + 가격, 수량에 문자가 들어가면 검증 오류 처리
+ 필드 검증
  + 상품명: 필수, 공백x
  + 가격: 1000원 이상, 1백만원 이하
  + 수량: 최대 9999
+ 특정 필드의 범위를 넘어서는 검증
  + 가격 * 수량의 합은 10,000원 이상
  
## 학습 내용
+ BindingResult
+ FieldError, ObjectError
+ 오류 코드와 메시지 처리
+ Validator 분리

+ Bean Validation
  + groups
  + Form 전송 객체 분리
  + HTTP 메시지터컨버터
