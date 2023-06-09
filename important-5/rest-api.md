# REST API란?

[REST](#gear-REST)원칙을 적용하여 서비스 [API](#gear-API)를 설계한 것을 말한다.

### REST란 무엇인가?

- [자원](#gear-자원)을 이름으로 구분하여 해당 자원의 상태를 주고 받는 모든 것이다. HTTP [URL](#gear-URL)를 통해 자원을 명시하고 HTTP 메서드(POST,GET,PUT,DELETE)를 통해 해당 자원에 대한 [CRUD](#gear-CRUD)를 적용하는 것을 말한다.
- 즉, 자원 기반의 구조 설계의 중심에 자원이 있고, HTTP 메서드를 통해 이를 처리한다.

### API란 무엇인가?

- 응용프로그램에서 사용할 수 있도록 운영 체제나 프로그래밍 언어가 제공하는 기능을 제어할 수 있게 만든 인터페이스이다.

- 쉽게 말해 프로그램끼리 통신할 수 있도록 하는 중재자이다.

---

## 용어 공부

### REST

- REpresentatioanl State Transfer의 약자로 전반적인 웹 어플리케이션에서 상호작용하는데 사용되는 웹 아키텍쳐 모델이다. 즉, 자원을 주고받는 웹 상에서의 통신 체계에 있어서 범용적인 스타일을 규정한 아키텍쳐 라고 할 수 있다.

### API

- Application Programming Interface의 약자로 구글 맵 API, 카카오 비전 API등 기존에 있는 응용 프로그램을 통해서 데이터를 제공 받거나 기능을 사용하고자 할 때 사용하는 인터페이스 및 규격 을 말한다. API는 프로그래밍 언어, 운영체제 등에서도 사용되는 범용적인 용어이다.따라서, REST API라는 것은 REST 원칙을 적용하여 서비스 API를 설계한 것읋 말하며 대부분의 서비스가 REST API를 제공한다.

### 자원

- 자원(Resource)은 문서,그림,DB,이미지,동영상, 해당 소프트웨어 자체 등의 웹에서 사용되는 모든 자료를 의미한다.

### URI

- URI는 Uniform Resource Identifier의 약자이며, 리소스(잔화, 지도, 이미지, 텍스트)에 접근할 수 있는 유일한(Uniform) 식별자(Identifier)를 의미한다. URI를 수신하는 기기는 해당 URI에 맞게 데이터를 반환한댜.

### CRUD

- CRUD는 대부분의 컴퓨터 소프트웨어가 가지는 기본적인 데이터 처리 기능인 Create, Read, Update, Delete를 묶어서 일컫는 말이다. 사용자 인터페이스가 갖추어야 할 기능(정보의 참조/검색/갱신)을 가리키는 용어로서 사용된다.
