numbers 리스트의 항목 중 짝수인 것만 필터링 해서
yesuit에 저장한 후 출력하세요
numbers=[111,26,37,48]


# numbers 리스트 정의
numbers = [111, 26, 37, 48]

# filter() 함수와 lambda 함수를 사용하여 짝수를 필터링하여 yesuit에 저장
yesuit = list(filter(lambda x: x % 2 == 0, numbers))

# 결과 출력
print("짝수만 필터링된 리스트:", yesuit)

<실행 코드>
numbers = [111, 26, 37, 48]

yesuit = list(filter(lambda x: x % 2 == 0, numbers))

print(yesuit)




위 코드에서 lambda 함수 (lambda x: x % 2 == 0)는 입력값이 짝수인지 여부를 확인합니다. 
filter() 함수를 사용하여 numbers 리스트에서 lambda 함수를 만족하는 요소들을 필터링하고, 
그 결과를 리스트로 변환하여 출력합니다.
