# 김영한님 스프링 부트와 JPA 강의 정리

## Recompile

build.gradle dependencies 에 아래 코드 추가
``` 
implementation 'org.springframework.boot:spring-boot-devtools'
```
그리고 재시작

### Mac 기준
command + shift + F9 또는 Build - Recompile

### 이걸 어디에 쓰나?
템플릿을 다루다 보면 바뀌는 내용이 많은데 개발중에 변경사항을 저장하려면 서버를 재부팅해야 한다.

스프링 다시 시작하려면? 빌드를 처음부터 해야한다. -> 시간이 오래 걸린다

그래서 파일 하나만 리컴파일해서 시간을 아낄 수 있다.

