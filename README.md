# Algorithm_study_2024
2024년 08월 15일에 개설한 알고리즘 스터디 입니다. 

1. 스터디 참여 인원 
2. 규칙 
3. branch 정책
4. 알고리즘 플랫폼 
5. 폴더 구조 
6.  PR 양식 



### 스터디 참여 인원

김민지, 천현태 , 주해린 

# 규칙 

- 주에 4문제 이상 풀이 (최소 갯수로 생각한 건데 유지 할지 갯수 늘릴지 토의 필요)

- 문제 난이도 [ 프로그래머스 LV.2 이상, 백준 실버 1이상 ] - 해당 난이도 이하 문제 풀이 시 * 2배 갯수 적용 

  ex) 해당 난이도 문제 3문제 + 이하 문제 2문제 = pass 

- 해당 주 목표 실패 시 벌금 2만원 납부 - (직장인이니까 1 야근을 기준으로 책정 했습니다)

- 월요일 8시 이전까지 main 브랜치에 merge 기준으로 벌금 책정 

- (논의 필요) 문제 선택 자율 or 필수 문제 지정 



# 알고리즘 플랫폼 

1. [codility](https://www.codility.com/)
2. [프로그래머스](https://school.programmers.co.kr/learn/challenges?order=acceptance_desc&page=1)
3. [백준](https://www.acmicpc.net/)
4. [SW Expert Academy](https://swexpertacademy.com/main/main.do)



# 폴더 구조

### 플랫폼 / [문제번호] 문제 이름 / 문제 번호 _작성자이름.py 

ex) programmers/ [1260]bfs와 dfs /1260_minji.py

- codility
- programmers 
- BOJ
- SWEA 

# 브랜치 정책

- main : 매주 월요일마다 각자 알고리즘 풀이 merge 
- feature/개인이름: 개인 알고리즘 풀이 branch, 해당 브랜치에 자기가 푼 알고리즘 풀이 업로드 

### Commit 

"[사용 알고리즘] 번호  문제이름  이름 "

ex) git commit -m "[DP] 설탕배달 2839 김민지 "

# PR 양식

## PR 제목

![image](https://user-images.githubusercontent.com/31977543/94366306-44307e80-0112-11eb-80d3-95a5e4998e64.png)

### [알고리즘 분류] 문제 제목 label : 문제 플랫폼, 언어 , 난이도 

### 문제 플랫폼:

- codility
- programmers 
- BOJ
- SWEA 

### 언어: 

* Javascript
*  python
*  java
*  c++
*  c ...

### 난이도:

* HARD
* NOMAL
* EASY

## PR 본문

1. 문제 출저 
2. input , output 설명 
3. 풀이 아이디어 

### PR 본문 예시 

### ex) 

1. 문제 출처 : https://programmers.co.kr/learn/courses/30/lessons/43238

2. input 및 output

   * input : n(인원수), times (심사위원당 걸리는 시간 list)

   * output: 심사하는데 걸리는 최소 시간

3. 풀이 아이디어 

   * 범위가 매우 크기 때문에 브루트 포스는 못하겠다는 생각이 들었고, 이분 탐색을 적용
     시간을 기준으로 이분 탐색을 적용하였고, 그 시간에 최대 몇 명의 인원을 심사할 수 있는지를 기준으로 start, end값을 조정해줌.
   * 초반에 start, end의 초기값을 대략적으로 잡아놓은 다음에 여러 값을 시도해서 정답을 검출했음.
