# java-programming
# 자바 크리에이트 -> name : Myfirst -> 모듈 해제 체크 -> finish => class 클릭 -> name : Hello2030 -> public static void main 클릭
# https://docs.oracle.com/javase/10/docs/api/ -> 2번째 줄 framse 클릭 이후 base 클릭 이후 java.lang

# 자바 1장 : 
# 윈도우 사회에서는 바이트 코드, 자바 사회에서는 클래스 파일이라고 부른다. 자바는 os, 플렛폼이 달라도 실행 가능? -> 자바를 기계어로 만들어 공유하면 가능. 자바는 컴파일 한번 jvm이 기계어로 한번 번역함 컴파일한 파일은 플렛폼이 달라지면 jvm이 달라져서 실행이 안될 수도 있음
# project 파일에서 소스코드를 만들면 .java로 만들어지는데 이를 컴파인 하면 project 안에 class 파일로 저장됨

# 자바 2장 :
# Integer.toBinaryString, Integer.toOctalString, Integer.toHexString를 습관적으로 사용하면 좋음
# 10진수에는 9의 보수, 10의 보수가 있다. 어떻게 구하는지도 알고 있자!
# 128, 256 2진수 구해보기에 적혀있는 정답이 옳은건지? 옳다면 왜 옳은건지 확인하기
# 뺄셈을 진행할 때는 2의 보수를 구해 더해주면 구해지니 빼기 기능이 없다.
# 자바에서는 overflow가 안일어난다? -> 2진수 최대값에서 1을 더하면 최솟값이 나옴 여기에 1을 더 더하면 오버플로우?
# 자바의 보수 연산자는 ~(tilda)

public class Hello2030 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("KIM KYOUNG ROK");
		System.out.println("CNU");
		int i = -1;
		System.out.println(Integer.toBinaryString(i));


	}

}
class A{}
class B{}
