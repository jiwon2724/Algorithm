## 문제 출처

<a href="https://school.programmers.co.kr/learn/courses/30/lessons/12951">JadenCase 문자열 만들기</a>

## 🔍 풀이
- 문제 설명대로 구현

## ✏️ 추가 지식
X


## 코드

```kotlin
class Solution {
fun solution(s: String): String = 
    s.lowercase().split(" ").joinToString(" ") { it.replaceFirstChar { it.uppercase()} }
}
```
