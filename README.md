# Java_1004  
  
  
  
sql에서    
procedure  
절차적으로 수행하는 프로그램  
  
insert into mm values(2,'aaa','a',30);  
데이터 자료형은 이상이 없지만  
입력되면 안된다  
  
  
3번째값은 m w만 와야함  
  
  
자바에서 함수를 공부할 때  
함수를 정의  
함수를 호출  
호출시 매개변수를 전달  
결과값 리턴  

  ![image](https://user-images.githubusercontent.com/80766275/193739493-36e4ce7b-dce5-4907-a82d-001d6874d68f.png)
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/193741149-cf7ba354-84f3-4471-afa3-e75af4b355a1.png)
같은 이름의 프롷시져를 제거하고 다시 만드는것  
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/193741438-47caa392-ea4a-4c35-8d96-07da05b790bd.png)
매개변수를 여러개 넣어서 프로시져 만드는 방법  
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/193746591-e4fef680-314c-4750-85c0-a9086f057d9f.png)
  
  
  
  
  
select 에서 주의할 점은 결과값이 단일값이냐 ,다중행이냐 구분해야 한다. 아래 예제는 단일행 단일값에만 정상 작동한다.  
만약dbms_output.put()명령어가 있는데도 콘솔에 출력되지 않으면  
set serverout.put()으로 콘솔 출력이 가능하도록 설정한다  
![image](https://user-images.githubusercontent.com/80766275/193745840-9a81418a-e54e-4490-a39f-3b0e67f027e1.png)


  
  
--------------------------------------  
  
  
디비 최적화 하는 방법  
  
1.물리적 구조화 최적화
2.메모리 할당 최적화
3.입력과 출력 분산 최적화
4.메모리 경합 최적화  
  
  
trace 명령어로 데이터베이스를 분석할 수 있다  
분석 가능한것은 물리적 reads 논리적 reads 처리된 튜플 수 ,파상이 발생할 때의 사용자  
커밋과 롤백등이 있다  
  
인덱스는 검색속도를 빠르게 해 주지만 무조건 생성하는것은 아니다  
성능의 엑서스를 고려하여 설정한다  
실행계획(어떤 실행의 결과물을 출력할것인가)를 고려하여 열 순서를 변경 추가한다  
사용하지 않은 인덱스는 제거한다  
  
  
  
  


  
  
  
  

  
