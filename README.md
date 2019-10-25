# python-2
>>> value=90
>>> if(value>=80):
	print("마스크를 쓰세요")
else:
	print("미세먼지가 좋습니다.")


마스크를 쓰세요
>>> 
관계연산자
>>> 1==1
True
>>> 1==2
False
>>> 2>=1
True
>>> 1>=2
False
>>> 1!=2
True
>>> 1!=1
False
>>> 'Apple'=='apple'
False
>>> 'Apple'=='Apple'
True
>>> 1=='1'
False
>>> 1==1.0
True
>>> 1==1
True
>>> val=10
>>> val>=5
True
>>> score=95
>>> if score>=90:
	print("가수입니다.")

	
가수입니다.
>>> 

score = int(input('숫자 입력하셈'))

if (score %2==0):
    print("짝수입니다")
else :
    print("홀수입니다")

score = int(input('숫자 입력하셈'))

if score >=90:
    print("A입니다.")
elif score >=80 :
    print("B입니다.")
elif score >=70 :
    print("C입니다.")
elif score >=60:
    print("D입니다.")
elif score >=70 :
    print("E입니다.")
else :
    print("F입니다.")

이중if문
새파일 : rain = int(input("강수량을 입력하세요:"))

if rain >0:
    if rain >=40:
        print("우비를 입으세요")
    else:
        print("우산을 쓰세요")
else:
        print("그냥 나가셔도 되요")
        
F5 누르고        
================ RESTART: C:/Users/pc/Desktop/ㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋ.py ================
강수량을 입력하세요:20
우산을 쓰세요
>>> 
================ RESTART: C:/Users/pc/Desktop/ㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋ.py ================
강수량을 입력하세요:80
우비를 입으세요
>>> 
score =int(input("수 입력:"))

if score >=0 :
    if score==0:
        print("0이다.")
    else:
        print("양수다.")
else:
    print("음수야.")
           
==================== RESTART: C:/Users/pc/Desktop/ㅎㅎㅎㅎ.py ====================
수 입력:6
양수다.
>>> 
==================== RESTART: C:/Users/pc/Desktop/ㅎㅎㅎㅎ.py ====================
수 입력:-2
음수야.
>>> 
==================== RESTART: C:/Users/pc/Desktop/ㅎㅎㅎㅎ.py ====================0
수 입력:0
0이다.

users=['choi','lee','kim']

id = input('아이디:') 
if id in users:
    pw=input('암호:')
    if pw=='1111':
        print("사용자 맞음")
    else :
       print(" 암호 틀림")
else :
    print("입력된 사용자가 아님")

==================== RESTART: C:/Users/pc/Desktop/999.py ====================
아이디:choi
암호:1111
사용자 맞음
>>> 
==================== RESTART: C:/Users/pc/Desktop/999.py ====================
아이디:lee
암호:5666
 암호 틀림
>>> 
==================== RESTART: C:/Users/pc/Desktop/999.py ====================
아이디:bang
입력된 사용자가 아님
