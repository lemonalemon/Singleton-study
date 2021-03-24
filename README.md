# Singleton-study

싱글톤이란?


싱글톤 패턴의 특징

1. 오직 한 개의 클래스 인스턴스만 갖도록 보장한다.
- 파일 시스템 클래스로 들어온 호출이 이전 작업 전체에 대해서 접근할 수 있게 해야함.
  (아무데서나 클래스 인스턴스를 만들 수 있으면 다른 인스턴스에서 어떤 작업을 진행 중인지 알 수 없기 때문)

2. 하나의 클래스 인스턴스를 전역에서 접근할 수 있는 방법을 제공한다.
- 누구든지 인스턴스에 접근할 수 있다.
- 싱글턴을 필요로 할 때까지 인스턴스 초기화를 미루는 역할을 한다. -> 한번도 사용하지 않으면 초기화되지 않는다. 
  

단점: 싱글톤 사용 중 크기가 커질 수 있다(싱글톤 오브젝트에 다 때려넣어서 객체가 아주 커질수있다)

(프라이빗에 생성자 만드는것이 중요
퍼블릭에서는 그 인스턴스를 사용할 수 있게 만드는 그것.
생성자를 한번만 해도 그 인스턴스를 사용할 수 있게 된다.)

