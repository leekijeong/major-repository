해시란?

key와 value 두쌍으로 이루어진 데이터이다
key 를 사용해서 value 를 찾는다
파이썬에서는 딕셔너리 자료형이 해시테이블과 같은구조

검색 저장 삭제가 잦은경우 사용하면 효율적

해시구조:
 
키(Key): 입력 데이터 
 
값(value): 저장할 데이터 

해쉬 함수(Hash Function): '키'를 해시로 변경해주는 함수

해시(Hash): 인풋 데이터를 고정된 길이의 숫자열로 변환한 결과물

즉 인풋데이터를 해시함수를 거쳐 해시가 값을 찾을수있게해줌

문제점: 해시충돌
    충돌을 막기위해 오픈해싱과, 클로즈해싱이있다.

    
https://jinyes-tistory.tistory.com/10


https://programmers.co.kr/learn/courses/30/lessons/42576