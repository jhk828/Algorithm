# Algorithm

-------------------

> - since 210119~
>
> - 1일 1 commit  목표
> - 문제 사이트별로, 날짜 순으로 기록합니다.
> - README에 기록하지 않으며 풀던 문제들은 복습하며 추가 중 입니다.



## 백준

| 문제번호                                                     | 풀이                                                         | 문제명             | 분류                      | 날짜                                 | memo                                                         | 복습 필요 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------ | ------------------------- | ------------------------------------ | ------------------------------------------------------------ | --------- |
| [1158](https://www.acmicpc.net/problem/1158)                 | [1158](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1158_%EC%9A%94%EC%84%B8%ED%91%B8%EC%8A%A4%EB%AC%B8%EC%A0%9C.java) | 요세푸스문제       | `큐`                      | 21/02/09                             |                                                              | ☑         |
| [1260](https://www.acmicpc.net/problem/1260)                 | [1260](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1260_DFS%EC%99%80BFS.java) | DFS와 BFS          | `DFS` `BFS`               | 21/02/12<br />21/03/16               |                                                              |           |
| [2206](https://www.acmicpc.net/problem/2206)                 | [2206](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_2206_%EB%B2%BD%EB%B6%80%EC%88%98%EA%B3%A0%EC%9D%B4%EB%8F%99%ED%95%98%EA%B8%B0.java) | 벽 부수고 이동하기 | `BFS`                     | 21/02/14<br />21/03/17               | [1. visited 배열 3차 -> 벽 부실때, 부시지 않을 때 구분<br />2. 전에 벽을 부셨을 때 보다 더 적은 칸수로 나아갈 수 x](https://jhk0307.tistory.com/302) |           |
| [7576]([www.acmicpc.net/problem/7576](https://www.acmicpc.net/problem/7576)) | [7576](https://github.com/jhk828/Algorithm/blob/8c1c14cfa93b0eae0b5329bab196915f1460b69b/BJ/Main_BJ_7576_%ED%86%A0%EB%A7%88%ED%86%A0.java) | 토마토             | `BFS`                     | 21/03/02<br />21/04/14               | [bfs](https://jhk0307.tistory.com/326)                       |           |
| [9663](https://www.acmicpc.net/problem/9663)                 | [9663](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_9663_NQueen.java) | N-Queen            | `백트랙킹`                | 21/03/02                             | [1행/ 1열/ 1대각선 -> 1퀸](https://jhk0307.tistory.com/328)  |           |
| [17135](https://www.acmicpc.net/problem/17135)               | [17135](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_17135_%EC%BA%90%EC%8A%AC%EB%94%94%ED%8E%9C%EC%8A%A4.java) | 캐슬 디펜스        | `시뮬레이션`              | 21/03/04                             | **A형 기출**<br />[1) 궁수들이 동시에 여러 적을 노릴 수 있음<br />2) Class의 `compareTo()` 재정의하여 사용하기](https://jhk0307.tistory.com/337) |           |
| [17406](https://www.acmicpc.net/problem/17406)               | [17406](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_17406_%EB%B0%B0%EC%97%B4%EB%8F%8C%EB%A6%AC%EA%B8%B04_2.java) | 배열 돌리기4       | `시뮬레이션` `순열`       | 21/02/10<br />21/03/05               | **A형 기출** <br />[1) 배열 복사해서 rotate()해야 다음 경우에 영향 x<br />2) `map[or][oc]` <- `map[nr][nc]` 순서 / 회전 순서 유의](https://jhk0307.tistory.com/300) |           |
| [3109](https://www.acmicpc.net/problem/3109)                 | [3109](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_3109_%EB%B9%B5%EC%A7%91.java) | 빵집               | `DFS` `백트랙킹`          | 21/02/20<br />21/03/06               | [가지치기 2가지<br />1) 성공하여 return true를 한 경우 다음 방향으로 탐색x<br />2) 3방 모두 탐색 불가능해도 `visited[r][c]`값 초기화x](https://jhk0307.tistory.com/327) |           |
| [17070](https://www.acmicpc.net/problem/3109)                | [17070](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_17070_%ED%8C%8C%EC%9D%B4%ED%94%84%EC%98%AE%EA%B8%B0%EA%B8%B01.java) | 파이프 옮기기1     | `시뮬레이션` `DFS`        | 21/03/06<br />21/03/15               | 방향(가로 / 세로 / 대각선)마다 다른 이동조건 확인<br /><br />두번째 파이프 위치만 가지고 풀기 | ☑         |
| [17281](https://www.acmicpc.net/problem/17281)               | [17281](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_17281_%EC%95%BC%EA%B5%AC_fail.java) | ⚾                  |                           | 21/03/09 ~ <br />21/03/10            | **A형 기출**<br />**미해결** - 순열/ nextPermutation으로 푸는 중 | ☑         |
| [16236](https://www.acmicpc.net/problem/16236)               | [16236](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_16236_%EC%95%84%EA%B8%B0%EC%83%81%EC%96%B4.java) | 아기상어           | `BFS`                     | 21/03/15<br />21/03/17               | [ArrayList Sort, Comparable, for each](https://jhk0307.tistory.com/344) |           |
| [1759](https://www.acmicpc.net/problem/1759)                 | [1759](https://github.com/jhk828/Algorithm/blob/b7cea277fe4b574d3c24a19626dfeefc197dfa17/BJ/Main_BJ_1759_%EC%95%94%ED%98%B8%EB%A7%8C%EB%93%A4%EA%B8%B0.java) | 암호만들기         | `조합` `DFS` `정렬`       | 21/03/16                             |                                                              |           |
| [14889](https://www.acmicpc.net/problem/14889)               | [14889](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_14889_%EC%8A%A4%ED%83%80%ED%8A%B8%EC%99%80%EB%A7%81%ED%81%AC.java) | 스타트와 링크      | `조합` `DFS`              | 21/03/17                             |                                                              |           |
| [17471](https://www.acmicpc.net/problem/17471)               | [17471](https://github.com/jhk828/Algorithm/blob/f24f3820a0a7e557f42068a6f854f48e7ac70720/BJ/Main_BJ_17471_%EA%B2%8C%EB%A6%AC%EB%A9%98%EB%8D%94%EB%A7%81.java) | 게리멘더링         | `DFS` `BFS` `그래프`      | 21/03/18<br />21/03/19<br />21/04/11 | **A형 기출**<br />DFS(팀나누기) + BFS(연결유무)              | ☑         |
| [1753](https://www.acmicpc.net/problem/1753)                 | [1753](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1753_%EC%B5%9C%EB%8B%A8%EA%B2%BD%EB%A1%9C.java) | 최단경로           | `최단경로` `Dijkstra`     | 21/03/22                             |                                                              | ☑         |
| [1786](https://www.acmicpc.net/problem/1786)                 | [1786](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1786_%EC%B0%BE%EA%B8%B0.java) | 찾기               | `문자열패턴` `KMP`        | 21/03/22                             |                                                              |           |
| [1463](https://www.acmicpc.net/problem/1463)                 | [1463](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1463_1%EB%A1%9C%EB%A7%8C%EB%93%A4%EA%B8%B0.java) | 1로 만들기         | `DP`                      | 21/03/23                             | [n=1일 때는 값이 1이 아니라 0이다](https://jhk0307.tistory.com/347) | ☑         |
| [1149](https://www.acmicpc.net/problem/1149)                 | [1149](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1149_RGB%EA%B1%B0%EB%A6%AC.java) | RGB 거리           | `DP`                      | 21/03/23                             | [.](https://jhk0307.tistory.com/348)                         |           |
| [2636](https://www.acmicpc.net/problem/2636)                 | [2636](https://github.com/jhk828/Algorithm/blob/fd021f783c3152d12b737dced1ed43f9e72314bb/BJ/Main_BJ_2636_%EC%B9%98%EC%A6%88.java) | 치즈               | `BFS` `시뮬레이션`        | 21/03/24                             | [내부/외부 구분 / `DFS`로 풀어보기](https://jhk0307.tistory.com/350) | ☑         |
| [1600](https://www.acmicpc.net/problem/1600)                 | [1600](https://github.com/jhk828/Algorithm/blob/fd021f783c3152d12b737dced1ed43f9e72314bb/BJ/Main_BJ_1600_%EB%A7%90%EC%9D%B4%EB%90%98%EA%B3%A0%ED%94%88%EC%9B%90%EC%88%AD%EC%9D%B4.java) | 말이되고픈원숭이   | `BFS` 시뮬레이션          | 21/03/24                             | [3차원 visited 배열](https://jhk0307.tistory.com/351)        |           |
| [9205](https://www.acmicpc.net/problem/9205)                 | [9205](https://github.com/jhk828/Algorithm/blob/e974d400f87aa161c18457d64cd43feb7ba136fa/BJ/Main_BJ_9205_%EB%A7%A5%EC%A3%BC%EB%A7%88%EC%8B%9C%EA%B8%B0.java) | 맥주마시기         | `BFS`                     | 21/03/25                             |                                                              |           |
| [14502](https://www.acmicpc.net/problem/14502)               | [14502](https://github.com/jhk828/Algorithm/blob/a99077fbc197109e0f5b2fa5390c1463cb57301d/BJ/Main_BJ_14502_%EC%97%B0%EA%B5%AC%EC%86%8C.java) | 연구소             | `DFS` `BFS` `시뮬레이션`  | 21/03/26                             |                                                              | ☑         |
| [2644](https://www.acmicpc.net/problem/2644)                 | [2644](https://github.com/jhk828/Algorithm/blob/a99077fbc197109e0f5b2fa5390c1463cb57301d/BJ/Main_BJ_2644_%EC%B4%8C%EC%88%98%EA%B3%84%EC%82%B0.java) | 촌수계산           | `BFS`                     | 21/03/26                             | q의 size만큼 poll 하여 자식 노드들 탐색                      | ☑         |
| [11650](https://www.acmicpc.net/problem/11650)               | [11650-1](https://github.com/jhk828/Algorithm/blob/028e14712e7b07dfdd8c5b0e34ebd1f139d9f209/BJ/Main_BJ_11650_%EC%A2%8C%ED%91%9C%EC%A0%95%EB%A0%AC%ED%95%98%EA%B8%B0_Comparable.java)<br />[11650-2](https://github.com/jhk828/Algorithm/blob/028e14712e7b07dfdd8c5b0e34ebd1f139d9f209/BJ/Main_BJ_11650_%EC%A2%8C%ED%91%9C%EC%A0%95%EB%A0%AC%ED%95%98%EA%B8%B0_Comparator.java) | 좌표정렬하기       | `Sort`                    | 21/03/28                             | [`Comparable` vs `Comparator `](https://jhk0307.tistory.com/323) |           |
| [11650](https://www.acmicpc.net/problem/11650)               | [11650](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_11651_%EC%A2%8C%ED%91%9C%EC%A0%95%EB%A0%AC%ED%95%98%EA%B8%B02.java) | 좌표정렬하기2      | `Sort`                    | 21/03/28                             |                                                              |           |
| [1181](https://www.acmicpc.net/problem/1181)                 | [1181](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1181_%EB%8B%A8%EC%96%B4%EC%A0%95%EB%A0%AC_2.java) | 단어정렬           | `Sort`                    | 21/03/28                             | `String` - `compareTo()`, `Iterator` - `hasNext`(), `next()` |           |
| [2108](https://www.acmicpc.net/problem/2108)                 | [2108](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_2108_%ED%86%B5%EA%B3%84%ED%95%99.java) | 통계학             | `Sort`                    | 21/03/28                             | 음수 범위의 수-> 양수화 하기                                 |           |
| [1427](https://www.acmicpc.net/problem/1427)                 | [1427](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1427_%EC%86%8C%ED%8A%B8%EC%9D%B8%EC%82%AC%EC%9D%B4%EB%93%9C.java) | 소트 인사이드      | `Sort`                    | 21/03/28                             | `Collections.reverseOrder()`                                 |           |
| [1026](https://www.acmicpc.net/problem/1026)                 | [1026](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1026_%EB%B3%B4%EB%AC%BC.java) | 보물               | `Sort`                    | 21/03/28                             |                                                              |           |
| [10825](https://www.acmicpc.net/problem/10825)               | [10825](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_10825_%EA%B5%AD%EC%98%81%EC%88%98.java) | 국영수             | `Sort`                    | 21/03/28                             | `String` - `compareTo()`                                     |           |
| [17472](https://www.acmicpc.net/problem/17472)               | [17472](https://github.com/jhk828/Algorithm/blob/90b63e7355963b462f507da19ba4590461f567cc/BJ/Main_BJ_17472_%EB%8B%A4%EB%A6%AC%EB%A7%8C%EB%93%A4%EA%B8%B02.java) | 다리만들기2        | `DFS` `BFS` `Prim`        | 21/03/29                             | Prim - 최소신장트리                                          | ☑         |
| [1755](https://www.acmicpc.net/problem/1755)                 | [1755](https://github.com/jhk828/Algorithm/blob/90b63e7355963b462f507da19ba4590461f567cc/BJ/Main_BJ_1755_%EC%88%AB%EC%9E%90%EB%86%80%EC%9D%B4.java) | 숫자놀이           | `Sort`                    | 21/03/29                             |                                                              |           |
| [2629](https://www.acmicpc.net/problem/2629)                 | [2629](https://github.com/jhk828/Algorithm/blob/90b63e7355963b462f507da19ba4590461f567cc/BJ/Main_BJ_2629_%EC%96%91%ED%8C%94%EC%A0%80%EC%9A%B8_fail.java) | 양팔저울           | `DP`                      | 21/03/29                             | **미해결**                                                   | ☑         |
| [16973](https://www.acmicpc.net/problem/16973)               | [16973](https://github.com/jhk828/Algorithm/blob/063404b757006639199e8b74ba660a16cd6cb1ac/BJ/Main_BJ_16973_%EC%A7%81%EC%82%AC%EA%B0%81%ED%98%95%ED%83%88%EC%B6%9C.java) | 직사각형 탈출      | `BFS`                     | 21/03/31                             | [직사각형 모든 넓이 체크-> 시간초과](https://jhk0307.tistory.com/354) |           |
| [12907](https://www.acmicpc.net/problem/12907)               | [12907](https://github.com/jhk828/Algorithm/blob/5c349daf755aae37e5b1aa4ed2107991bca3f1c2/BJ/Main_BJ_12907_%EB%8F%99%EB%AC%BC%EC%9B%90.java) | 동물원             |                           | 21/04/01                             |                                                              | ☑         |
| [1261](https://www.acmicpc.net/problem/1261)                 | [1261-1](https://github.com/jhk828/Algorithm/blob/f8968d36aa33aec9239fb2312fb2f9f9b4914e1c/BJ/Main_BJ_1261_%EC%95%8C%EA%B3%A0%EC%8A%A4%ED%8C%9F_pq.java)<br />[1261-2](https://github.com/jhk828/Algorithm/blob/master/BJ/Main_BJ_1261_%EC%95%8C%EA%B3%A0%EC%8A%A4%ED%8C%9F_dijkstra.java) | 알고스팟           | `BFS` `PQ` `Dijkstra`     | 21/04/03                             | BFS+우선순위큐 / BFS+Dijkstra                                | ☑         |
| [19236](https://www.acmicpc.net/problem/19236)               | [19236](https://github.com/jhk828/Algorithm/blob/e10648d8cf976033d0b01d6f6c0a7330e74c7762/BJ/Main_BJ_19236_%EC%B2%AD%EC%86%8C%EB%85%84%EC%83%81%EC%96%B4_fail.java) | 청소년 상어        | `시뮬레이션` `DFS`        | 21/04/04                             | **미해결** 대체 어디가 잘못된걸까                            | ☑         |
| [18352](https://www.acmicpc.net/problem/18352)               | [18352](https://github.com/jhk828/Algorithm/blob/2f07fddd98697807e3584bf987a14926c2c1cc82/BJ/Main_BJ_18352_%ED%8A%B9%EC%A0%95%EA%B1%B0%EB%A6%AC%EC%9D%98%EB%8F%84%EC%8B%9C%EC%B0%BE%EA%B8%B0.java) | 특정거리의도시찾기 | `BFS`                     | 21/04/05                             | 인접리스트 BFS                                               | ☑         |
| [18405](https://www.acmicpc.net/problem/18405)               | [18405](https://github.com/jhk828/Algorithm/blob/2f07fddd98697807e3584bf987a14926c2c1cc82/BJ/Main_BJ_18405_%EA%B2%BD%EC%9F%81%EC%A0%81%EC%A0%84%EC%97%BC.java) | 경쟁적전염         | `BFS`                     | 21/04/05                             | BFS - 크기만큼 돌리기                                        | ☑         |
| [17779](https://www.acmicpc.net/problem/17779)               | [17779](https://github.com/jhk828/Algorithm/blob/e97cba8903d44ca03683735b3fd27b3192ff5de3/BJ/Main_BJ_17779_%EA%B2%8C%EB%A6%AC%EB%A7%A8%EB%8D%94%EB%A7%812.java) | 게리멘더링2        | `시뮬레이션` `BruteForce` | 21/04/11                             | 배열 최대최소값: 정렬후첫/마지막원소                         | ☑         |
| [2564](https://www.acmicpc.net/problem/2564)                 | [2564](https://github.com/jhk828/Algorithm/blob/f5db1dbe89ffe4cfa3196ec8f41d0c06f4cbc53e/BJ/Main_BJ_2564_%EA%B2%BD%EB%B9%84%EC%9B%90.java) | 경비원             |                           | 21/04/13                             | 수식 구현                                                    |           |
| [19238](https://www.acmicpc.net/problem/19238)               | [19238](https://github.com/jhk828/Algorithm/blob/94a313d28d0c6e1311afe11bee07148835a37b1e/BJ/Main_BJ_19238_%EC%8A%A4%ED%83%80%ED%8A%B8%ED%83%9D%EC%8B%9C.java) | 스타트 택시        | `BFS`                     | 21/04/13                             | [가중치x 그래프 최단거리](https://jhk0307.tistory.com/356)   | ☑         |
| [19237](https://www.acmicpc.net/problem/19237)               | [19237](https://github.com/jhk828/Algorithm/blob/8c1c14cfa93b0eae0b5329bab196915f1460b69b/BJ/Main_BJ_19237_%EC%96%B4%EB%A5%B8%EC%83%81%EC%96%B4.java) | 어른상어           | `시뮬레이션`              | 21/04/14                             | [방향 우선 순위](https://jhk0307.tistory.com/357)            |           |
| [17144](https://www.acmicpc.net/problem/17144)               | [17144](https://github.com/jhk828/Algorithm/blob/8c1c14cfa93b0eae0b5329bab196915f1460b69b/BJ/Main_BJ_17144_%EB%AF%B8%EC%84%B8%EB%A8%BC%EC%A7%80%EC%95%88%EB%85%95.java) | 미세먼지안녕       | `시뮬레이션`              | 21/04/14                             | 사방탐색                                                     |           |



## SWEA

| 문제번호                                                     | 풀이                                                         | 문제명                           | 분류                        | 날짜                   | memo                                                         | 복습 필요 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------- | --------------------------- | ---------------------- | ------------------------------------------------------------ | --------- |
| [1873](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV5LyE7KD2ADFAXc&categoryId=AV5LyE7KD2ADFAXc&categoryType=CODE&problemTitle=%EB%B0%B0%ED%8B%80&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [1873](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_D3_1873_%EC%83%81%ED%98%B8%EC%9D%98%EB%B0%B0%ED%8B%80%ED%95%84%EB%93%9C.java) | 상호의 배틀필드                  | `시뮬레이션`                | 21/02/03               |                                                              | ☑         |
| [9229](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AW8Wj7cqbY0DFAXN&categoryId=AW8Wj7cqbY0DFAXN&categoryType=CODE&problemTitle=%ED%95%9C%EB%B9%88&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [9229]()                                                     | 한빈이와 Spot Mart               | `부분집합` `조합`           | 21/02/08               | 부분집합으로 nCr 구하기<br />`total`값을 부분집합 파라미터로 넘기기 |           |
| [5215](swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWT-lPB6dHUDFAVT&categoryId=AWT-lPB6dHUDFAVT&categoryType=CODE&problemTitle=%ED%96%84%EB%B2%84%EA%B1%B0&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [5215](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_D3_5215_%ED%96%84%EB%B2%84%EA%B1%B0%EB%8B%A4%EC%9D%B4%EC%96%B4%ED%8A%B8.java) | 햄버거 다이어트                  | `부분집합`                  | 21/02/08               | `total`값을 부분집합 파라미터로 넘기기                       |           |
| [6808](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWgv9va6HnkDFAW0&categoryId=AWgv9va6HnkDFAW0&categoryType=CODE&problemTitle=%EC%B9%B4%EB%93%9C%EA%B2%8C%EC%9E%84&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [6808](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_D3_6808_%EA%B7%9C%EC%98%81%EC%9D%B4%EC%99%80%EC%9D%B8%EC%98%81%EC%9D%B4%EC%9D%98%EC%B9%B4%EB%93%9C%EA%B2%8C%EC%9E%84_2.java) | 규영이와 인영이의 <br />카드게임 | `순열` `DFS`                | 21/02.14<br />21/03/13 | 순열로 팩토리얼                                              |           |
| [4012](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWIeUtVakTMDFAVH&categoryId=AWIeUtVakTMDFAVH&categoryType=CODE&problemTitle=4012&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1&&&&&&&&&#none) | [4012](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_%EB%AA%A8%EC%9D%98_4012_%EC%9A%94%EB%A6%AC%EC%82%AC_2.java) | 요리사                           | `부분집합`                  | 21/02/19<br />21/03/14 | [부분집합으로 nCr 구하기](https://jhk0307.tistory.com/341)   |           |
| [3234](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWAe7XSKfUUDFAUw&categoryId=AWAe7XSKfUUDFAUw&categoryType=CODE&problemTitle=%EC%A4%80%ED%99%98&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [3234](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_D4_3234_%EC%A4%80%ED%99%98%EC%9D%B4%EC%9D%98%EC%96%91%ED%8C%94%EC%A0%80%EC%9A%B8.java) | 준환이의 양팔저울                | `순열` `DFS`                | 21/02/19               |                                                              | ☑         |
| [1767](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV4suNtaXFEDFAUf&categoryId=AV4suNtaXFEDFAUf&categoryType=CODE&problemTitle=1767&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1&&&&&&&&&) | [1767](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_D_1767_%ED%94%84%EB%A1%9C%EC%84%B8%EC%84%9C%EC%97%B0%EA%B2%B0%ED%95%98%EA%B8%B0_2.java) | 프로세서 연결하기                | `부분집합` `백트래킹` `DFS` | 21/02/25<br />21/03/01 | [1) 전선 교차x <br />2) 4방향 모두 탐색할 필요 x](https://jhk0307.tistory.com/335) |           |
| [1749](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV5PoOKKAPIDFAUq&categoryId=AV5PoOKKAPIDFAUq&categoryType=CODE&problemTitle=1949&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1&&&&&&&&&) | [1749](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_%EB%AA%A8%EC%9D%98_1949_%EB%93%B1%EC%82%B0%EB%A1%9C%EC%A1%B0%EC%84%B1.java) | 등산로 조성                      | `DFS`                       | 21/03/11               | 새 위치의 등산로를 깎을 때, 현재값-1로 깎기 X                |           |
| [1952](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV5PpFQaAQMDFAUq&categoryId=AV5PpFQaAQMDFAUq&categoryType=CODE&problemTitle=%EC%88%98%EC%98%81%EC%9E%A5&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [1952](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_%EB%AA%A8%EC%9D%98_1052_%EC%88%98%EC%98%81%EC%9E%A5.java) | 수영장                           | `DFS`                       | 21/03/11               | `DP`로도 풀어보기                                            |           |
| [10966](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AXWXMZta-PsDFAST&categoryId=AXWXMZta-PsDFAST&categoryType=CODE&problemTitle=10966&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [10966](https://github.com/jhk828/Algorithm/blob/da93dad54800401aaecf45b0e859216a18c03239/SW%20Expert/Solution_D4_10966_%EB%AC%BC%EB%86%80%EC%9D%B4%EB%A5%BC%EA%B0%80%EC%9E%90.java) | 물놀이를 가자                    | `BFS`                       | 21/03/15               | [bfs는 여러개의 지점 동시 탐색](https://jhk0307.tistory.com/343) |           |
| [1227](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV14wL9KAGkCFAYD&categoryId=AV14wL9KAGkCFAYD&categoryType=CODE&problemTitle=%EB%AF%B8%EB%A1%9C2&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [1227](https://github.com/jhk828/Algorithm/blob/5cd65b89205cfcf18d469ed8fe7825f1eda952be/SW%20Expert/Solution_D4_1227_%EB%AF%B8%EB%A1%9C2.java) | 미로2                            | `BFS`                       | 21/03/15               |                                                              |           |
| [8382](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWyNQrCahHcDFAVP&categoryId=AWyNQrCahHcDFAVP&categoryType=CODE&problemTitle=8382&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [8382](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_D4_8382_%EB%B0%A9%ED%96%A5%EC%A0%84%ED%99%98_2.java) | 방향전환                         | `BFS`                       | 21/03/15<br />21/03/22 | [3원 visited 배열](https://jhk0307.tistory.com/342)          | ☑         |
| [4008](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWIeRZV6kBUDFAVH&categoryId=AWIeRZV6kBUDFAVH&categoryType=CODE&problemTitle=4008&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [4008](https://github.com/jhk828/Algorithm/blob/5cd65b89205cfcf18d469ed8fe7825f1eda952be/SW%20Expert/Solution_%EB%AA%A8%EC%9D%98_4008_%EC%88%AB%EC%9E%90%EB%A7%8C%EB%93%A4%EA%B8%B0.java) | 숫자 만들기                      | `재귀`                      | 21/03/16               | 재귀 함수 시작 인덱스 조심                                   |           |
| [1238](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV15B1cKAKwCFAYD&categoryId=AV15B1cKAKwCFAYD&categoryType=CODE&problemTitle=Contact&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [1238](https://github.com/jhk828/Algorithm/blob/b7cea277fe4b574d3c24a19626dfeefc197dfa17/SW%20Expert/Solution_D4_1238_Contact.java) | Contact                          | `BFS` `Graph`               | 21/03/16               |                                                              |           |
| [1486](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV2b7Yf6ABcBBASw) | [1486](https://github.com/jhk828/Algorithm/blob/master/SW%20Expert/Solution_D4_1486_%EC%9E%A5%ED%9B%88%EC%9D%B4%EC%9D%98%EB%86%92%EC%9D%80%EC%84%A0%EB%B0%98.java) | 장훈이의높은선반                 | `DFS`                       | 21/03/18               | 가지치기 조건들                                              |           |
| [1251](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV15StKqAQkCFAYD&categoryId=AV15StKqAQkCFAYD&categoryType=CODE&problemTitle=1251&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [1251](https://github.com/jhk828/Algorithm/blob/fd021f783c3152d12b737dced1ed43f9e72314bb/SW%20Expert/Solution_D4_1251_%ED%95%98%EB%82%98%EB%A1%9C.java) | 하나로                           | `MST` `Prim` `Kruskal`      | 21/03/24               |                                                              | ☑         |
| [1219](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV14geLqABQCFAYD&categoryId=AV14geLqABQCFAYD&categoryType=CODE&problemTitle=1219&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [1219](https://github.com/jhk828/Algorithm/blob/0591e5f09fb3bfbc8fee4e6a9ddb7574d327bde1/SW%20Expert/Solution_D4_1219_%EA%B8%B8%EC%B0%BE%EA%B8%B0.java) | 길찾기                           | `Graph`                     | 21/03/24               |                                                              |           |
| [3307](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWBOKg-a6l0DFAWr&categoryId=AWBOKg-a6l0DFAWr&categoryType=CODE&problemTitle=3307&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [3307](https://github.com/jhk828/Algorithm/blob/e974d400f87aa161c18457d64cd43feb7ba136fa/SW%20Expert/Solution_D3_3307_%EC%B5%9C%EC%9E%A5%EC%A6%9D%EA%B0%80%EB%B6%80%EB%B6%84%EC%88%98%EC%97%B4.java) | 최장증가수열                     | `LIS` `DP`                  | 21/03/25               |                                                              |           |
| [1263](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV18P2B6Iu8CFAZN&categoryId=AV18P2B6Iu8CFAZN&categoryType=CODE&problemTitle=1263&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [1263](https://github.com/jhk828/Algorithm/blob/a99077fbc197109e0f5b2fa5390c1463cb57301d/SW%20Expert/Solution_D6_1263_%EC%82%AC%EB%9E%8C%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC2.java) | 사람네트워크2                    | `Dijkstra`                  | 21/03/25               |                                                              |           |
| [1249](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AV15QRX6APsCFAYD&) | [1249](https://github.com/jhk828/Algorithm/blob/ba60d0397cb2f9ed84698dbdda619aa44e88ff1d/SW%20Expert/Solution_D4_1249_%EB%B3%B4%EA%B8%89%EB%A1%9C.java)<br />[1249-1](https://github.com/jhk828/Algorithm/blob/4bd4b0f7b7d7ec350eef23a3847ceb5c9525b466/SW%20Expert/Solution_D4_1249_%EB%B3%B4%EA%B8%89%EB%A1%9C_Dijkstra.java) | 보급로                           | `BFS` `Dijkstra`            | 21/04/12               | [가중치 있는 그래프 BFS -> PQ](https://jhk0307.tistory.com/355) |           |
| [5644](https://swexpertacademy.com/main/code/problem/problemDetail.do?contestProbId=AWXRDL1aeugDFAUo&categoryId=AWXRDL1aeugDFAUo&categoryType=CODE&problemTitle=5644&orderBy=FIRST_REG_DATETIME&selectCodeLang=ALL&select-1=&pageSize=10&pageIndex=1) | [5644](https://github.com/jhk828/Algorithm/blob/4bd4b0f7b7d7ec350eef23a3847ceb5c9525b466/SW%20Expert/Solution_%EB%AA%A8%EC%9D%98_5644_%EB%AC%B4%EC%84%A0%EC%B6%A9%EC%A0%84.java) | 무선충전                         |                             | 21/04/12               |                                                              |           |
| [5656](https://swexpertacademy.com/main/code/problem/problemSubmitHistory.do) | [5656](https://github.com/jhk828/Algorithm/blob/8c1c14cfa93b0eae0b5329bab196915f1460b69b/SW%20Expert/Solution_D4_5656_%EB%B2%BD%EB%8F%8C%EA%B9%A8%EA%B8%B0.java) | 벽돌깨기                         | `시뮬레이션`                | 21/04/14               |                                                              |           |



## Programmers

| 문제번호                                                     | 풀이                                                         | 문제명     | 분류              | 날짜     | memo                                   | 복습 필요 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------- | ----------------- | -------- | -------------------------------------- | --------- |
| [LV2 타겟넘버](https://programmers.co.kr/learn/courses/30/lessons/43165) | [LV2 타겟넘버](https://github.com/jhk828/Algorithm/blob/11dd67a4ebda2deed678ea583e23caafdd5e9b9f/Programmers/Programmers_LV2_%ED%83%80%EA%B2%9F%EB%84%98%EB%B2%84.java) | 타겟넘버   | `DFS`             | 21/04/06 |                                        |           |
| [LV3 가장먼노드](https://programmers.co.kr/learn/courses/30/lessons/49189) | [LV3 가장먼노드](https://github.com/jhk828/Algorithm/blob/11dd67a4ebda2deed678ea583e23caafdd5e9b9f/Programmers/Programmers_LV3_%EA%B0%80%EC%9E%A5%EB%A8%BC%EB%85%B8%EB%93%9C.java) | 가장먼노드 | `Graph` `BFS`     | 21/04/06 |                                        |           |
| [LV3 네트워크](https://programmers.co.kr/learn/courses/30/lessons/43162) | [LV3 네트워크](https://github.com/jhk828/Algorithm/blob/11dd67a4ebda2deed678ea583e23caafdd5e9b9f/Programmers/Programmers_LV3_%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC.java) | 네트워크   | `DFS`             | 21/04/06 |                                        |           |
| [LV3 단어 변환](https://programmers.co.kr/learn/courses/30/lessons/43163) | [LV3 단어 변환](https://github.com/jhk828/Algorithm/blob/2489e590ee560068e16c1f183dba61ae5bf92ced/Programmers/Programmers_LV3_%EB%8B%A8%EC%96%B4%EB%B3%80%ED%99%98.java) | 단어 변환  | `DFS`             | 21/04/07 |                                        |           |
| [LV3 여행경로](https://programmers.co.kr/learn/courses/30/lessons/43164) | [LV3_여행경로](https://github.com/jhk828/Algorithm/blob/ca47e4d12d87709d65a3db389f38e35453135aba/Programmers/Programmers_LV3_%EC%97%AC%ED%96%89%EA%B2%BD%EB%A1%9C.java) | 여향경로   | `DFS` `Stack`     | 21/04/08 |                                        |           |
| [LV3 입국심사](https://programmers.co.kr/learn/courses/30/lessons/43238) | [LV3 입국심사](https://github.com/jhk828/Algorithm/blob/bb13b9bd53e6cf2c51da9a774b7e65631bde922f/Programmers/Programmers_LV3_%EC%9E%85%EA%B5%AD%EC%8B%AC%EC%82%AC.java) | 입국심사   | `이분탐색`        | 21/04/09 |                                        | ☑         |
| [LV3_순위](https://programmers.co.kr/learn/courses/30/lessons/49191) | [LV3_순위](https://github.com/jhk828/Algorithm/blob/master/Programmers/Programmers_LV3_%EC%88%9C%EC%9C%84.java) | 순위       | `Graph``최단경로` | 21/04/10 | INF 초기화 주의 / 플루이드워샬알고리즘 | ☑         |



## Code Up

| 문제번호                                                  | 풀이                                                         | 문제명 | 분류          | 날짜                | memo             | 복습 필요 |
| --------------------------------------------------------- | ------------------------------------------------------------ | ------ | ------------- | ------------------- | ---------------- | --------- |
| [기초 100제](https://codeup.kr/problemsetsol.php?psid=23) | [1~49번](https://github.com/jhk828/Algorithm/tree/master/CodeUp/CodeUp100%EC%A0%9C/1~49)<br />[50~100번](https://github.com/jhk828/Algorithm/tree/master/CodeUp/CodeUp100%EC%A0%9C/50~100) |        | `Java 사용법` | 21/01/19 ~ 21/01/16 | 입출력 방법 주의 |           |



## JUNGOL

| 문제번호                                                     | 풀이                                                         | 문제명         | 분류          | 날짜     | memo                           | 복습 필요 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------- | ------------- | -------- | ------------------------------ | --------- |
| [1863](http://www.jungol.co.kr/bbs/board.php?bo_table=pbank&wr_id=1136&sca=99&sfl=wr_hit&stx=1863) | [1863](https://github.com/jhk828/Algorithm/blob/master/JUNGOL/Main_JO_1863_%EC%A2%85%EA%B5%90.java) | 종교           | `서로소집합`  | 21/03/18 | Union-Find연산, 집합 개수 세기 | ☑         |
| [1681](http://jungol.co.kr/bbs/board.php?bo_table=pbank&wr_id=954&sca=99&sfl=wr_hit&stx=1681) | [1681](https://github.com/jhk828/Algorithm/blob/311758f10e5837695e996bea264ae9aa984e5cff/JUNGOL/Main_JO_1681_%ED%95%B4%EB%B0%80%ED%84%B4%EC%88%9C%ED%99%98%ED%9A%8C%EB%A1%9C.java) | 해밀턴순환회로 | `Graph` `DFS` | 21/03/22 | 1로 돌아올 때 길 있는지 체크   | ☑         |



