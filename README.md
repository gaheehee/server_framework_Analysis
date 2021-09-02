# ✏️<mark>server framework 분석</mark>   

<br>

### **Framework**
소프트웨어의 구체적인 부분에 해당하는 설계와 구현을 재사용이 가능하게끔 일련의 협업화된 형태로 클래스들을 제공하는 것

<br>

### **Framework 특징**
* Modularity 모듈화

    캡슐화를 통해 모듈화를 강화하고 설계와 구현의 변경에 따른 영향을 최소화하여 소프트웨어의 품질을 향상시킴

* Reusability 재사용성

    재사용 가능한 모듈들을 제공함으로써 개발자의 생산성을 향상시킴

* Extensibility 확장성

    프레임워크는 다형성을 통해 인터페이스의 확장이 가능하여 다양한 형태와 기능을 가진 애플리케이션 개발이 가능함

* Inversion of Control 제어의 흐름

    프레임워크 코드가 전체 애플리케이션의 처리 흐름을 제어하여 특정한 이벤트가 발생할 때 다형성을 통해 애플리케이션의 확장한 메소드를 호출함으로써 제어가 프레임워크로부터 애플리케이션으로 거꾸로 흐르게 함

<br>

### **Server Framework**
서버 프로그램 개발 시 다양한 네트워크 설정, 요청 및 응답처리, 아키텍처 모델 구현등을 손쉽게 처리할 수 있도록 클래스나 인터페이스를 제공하는 소프트웨어임

서버 개발 프레임워크에 따라 지원하는 프로그래밍 언어가 제한적이므로 선정할 수 있는 프레임워크도 제한적임

서버 개발 프레임워크의 대부분은 모델-뷰-컨트롤러 MVC패턴을 기반으로 개발됨

<br>

### <mark>**각종 Server Framework들**</mark>

<br>

| framework | 기반 언어 | 장점 | 단점 |
| ---- | ---- | ---- | ---- |
| Spring | JAVA | bean 설정 방법이 쉬움. </br> 서블릿 컨테이너에서 실행이 가능하므로 이식성(Portability)이 뛰어남. </br> 특정 인터페이스에 종속되지 않은 POJO를 기반으로 하기 때문에 테스트가 용이함. </br> AOP의 지원으로 EJB 컨테이너에서 지원 가능했던 컨테이너 기능들을 지원하는 것이 가능함. </br> OOP(Object Oriented Programing)형태로 개발하는 데 제약사항이 없음. | 분산 환경을 지원하지 못함. </br> (그러나 최근 웹 서비스와 같은 분산 환경 기술이 발전하면서 이 부분은 충분히 극복할 수 있음) </br> 아직까지 Lightweight 컨테이너의 표준이 없음 |
| Node.js | JavaScript | 구글의 크롬 V8 자바스크립트 엔진을 기반으로 한, 고성능 네트워크 서버임 </br>  비동기 입,출력 처리와 이벤트 위주의 높은 성능을 가짐. </br> 실시간으로 입/출력이 빈번함. | ㅇㅇ |
| Django | Python | 컴포넌트의 재사용과 플러그인화를 강조하여 신속한 개발이 가능함. </br>  | ㅇㅇ |
| RUby on Rails | Ruby | 테스트를 위한 웹서버를 지원함. </br> 데이터베이스 작업을 단순화, 자동화시켜 개발 코드의 길이가 짧다. </br> | ㅇㅇ |
<br>
