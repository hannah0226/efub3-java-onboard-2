# 자바 핵심 개념 정리 2
<details>
<summary>JAVA의 접근 제어자의 종류와 특징에 대해 설명해주세요.</summary>
<div markdown="1">
1. public: 모든 패키지, 모든 클래스에서 접근 가능<br>
2. protected: 같은 패키지의 모든 클래스 또는 다른 패키지에 있어도 자식 클래스일 경우 접근 허용<br>
3. default: 동일한 패키지 내에 있는 클래스만 접근 가능<br>
4. private: 오직 해당 멤버를 선언한 클래스에서만 접근 가능<br>
</div>
</details>
<br>

<details>
<summary>OOP의 5대 원칙 (SOLID)에 대해 설명해주세요.</summary>
<div markdown="1">
SOLID란? 객체지향 프로그래밍을 하면서 지켜야하는 5대 원칙으로 SRP(단일 책임 원칙), OCP(개방-폐쇄 원칙), LSP(리스코프 치환 원칙), DIP(의존 역전 원칙), ISP(인터페이스 분리 원칙) 의 앞글자를 따와서 만들어졌다.SOLID란? 객체지향 프로그래밍을 하면서 지켜야하는 5대 원칙으로 SRP(단일 책임 원칙), OCP(개방-폐쇄 원칙), LSP(리스코프 치환 원칙), DIP(의존 역전 원칙), ISP(인터페이스 분리 원칙) 의 앞글자를 따와서 만들어졌다.<br><br>
- 단일 책임 원칙: 모듈이 변경되는 이유가 한가지여야함. 해당 모듈이 여러 대상 또는 액터들에 대해 책임을 가져서는 안되고, 오직 하나의 액터에 대해서만 책임을 져야한다.<br>
- 개방 폐쇄 원칙: 확장에 대해 열려있고 수정에 대해서는 닫혀있어야 한다.<br>
- 인터페이스 분리 원칙: 목적과 관심이 각기 다른 클라이언트가 있다면 인터페이스를 통해 분리해줘야 한다. 모든 클라이언트가 자신의 관심에 맞는 퍼블릭 인터페이스만을 접근하여 불필요한 간섭 최소화<br>
- 리스코프 치환 원칙: 하위 타입은 상위 타입을 대체할 수 있어야한다. 즉, 해당 객체를 사용하는 클라이언트는 상위 타입이 하위 타입으로 변경되어도, 차이점을 인식하지 못한 채 상위 타입의 퍼블릭 인터페이스를 통해 서브 클래스를 사용할 수 있어야 한다.
</div>
</details>
<br>

<details>
<summary>non-static 멤버와 static 멤버의 차이에 대해 설명해주세요.</summary>
<div markdown="1">
non-static 멤버<br>
- 공간적 특성: 객체마다 별도로 존재한다.(인스턴스 멤버라고 부름)<br>
- 시간적 특성: 객체 생성시 멤버가 생성된다.<br>
- 비공유 특성: 맴버들은 다른 캑체에 의해 공유되지 않는다.<br><br>
static 멤버<br>
- 공간적 특성: 멤버들은 클래스 당 하나만 생성된다.<br>
- 시간적: 클래스가 로딩될 때 공간이 할당된다.<br>
- 공유의 특성: 동일한 클래스의 모든 객체에 의해 공유된다.
</div>
</details>
<br>

<details>
<summary>클래스, 객체, 인스턴스의 차이에 대해 설명해주세요.</summary>
<div markdown="1">
- 클래스란? 객체를 만들어내기 위한 설계도 혹은 틀<br>
- 객체란? 소프트웨어 세계에 구현할 대상<br>
- 인스턴스란? 설계도를 바탕으로 소프트웨어 세계에 구현된 구체적인 실체<br><br>

</div>
</details>
<br>

<details>
<summary>⭐️ 프로세스, 스레드, 멀티프로세스, 멀티스레드에 대해 설명해주세요.</summary>
<div markdown="1">
- 프로세스: 프로그램을 메모리 상에서 실행중인 작업을 말한다. 운영체제로부터 시스템 자원을 할당받는 작업의 단위이다.<br>
- 스레드: 프로세스 안에서 실행되는 여러 흐름의 단위이다. 기본적으로 프로세스마다 최소 1개의 스레드를 보유하고 있다.<br>
- 멀티프로세스: 여러 프로세스를 병렬적으로 처리하는 작업이다.<br>
- 멀티 스레드: 하나의 프로그램에서 여러 스레드를 구성해 각 스레드가 하나의 작업을 처리하는 것이다. 스레드들이 공유 메모리를 통해 다수의 작업을 동시에 처리하도록 해준다.
</div>
</details>
<br>
