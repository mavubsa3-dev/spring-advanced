# SPRING ADVANCED

## Lv 0 프로젝트 세팅
application.yml에 secretKey 생성 및 DB 생성해서 에러 해결

## Lv 1 ArgumentResolver
WebMvcConfiguer에 등록해서 ArgumentResolver 구현 및 사용

## Lv 2 코드 개선
### 2-1 Early Return
코드의 위치를 맨 위로 올려서 존재하지 않으르 경우 encode()동작이 일어나지 않도록 함

### 2-2 불필요한 if-else 피하기
if-else 대신 if문으로 조건 나눠서 검사하도록 수정

### 2-3 Validation
gradle에 의존성 주입
컨트롤러의 각 메서드마다 @Valid 어노테이션 추가해서 검사하도록 함

## Lv 3 N+1 문제
@EntityGraph 통해 해결

## Lv 4 테스트 코드
출력되는 에러와 출력되어야하는 에러 통일