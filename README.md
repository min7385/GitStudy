"Hello, Git!" 

# Markdown이란?
markdown은 텍스트를 서식 있는 문서로 쉽게 변환할 수 있는 마크업 언어. 2004년에 개발 되었으며, 문서를 작성하는데 사용되는 간단한 형식으로, HTML로 변환하기 쉽게 설계되었다.
markdown의 주 목적은 사람들이 읽기 쉽고 쓰기 쉬운 서식 문서를 만드는 것.

# 마크업 언어란?
마크업 언어는 텍스트에 태그를 사용하여 문서의 구조와 서식을 정의하는 언어
컴퓨터가 텍스트를 처리하는 데 도움이 되며, 문서를 체계적으로 작성하고 읽을 수 있도록 함.
마크업 언어의 예로는 HTML, XML, ... 등이 있음.

# HTML이란?
웹 페이지를 작성하는데 사용되는 표준 마크업 언어.
웹 페이지의 구조를 정의하며 텍스트, 이미지, 링크, 표, 폼 등을 웹 브라우저에서 표시할 수 있도록 함.

1. **헤더(Headers)** :
```
    백틱(`) 3개 = 코드라인 <-- markdown 문법이 적용 안됨.
    # 헤더1
    ## 헤더2
    ### 헤더3
```
## 헤더2
### 헤더3

2. 굵게
``` **굵게*** ```
**굵게**

3. 기울임
``` *기울임* ```
*기울임*

4. 목록

```
 1. 첫 번째
 2. 두 번째
 ```
 ### 순서가 없는
 ```
  - 첫 번째
  - 두 번째
  ```
  - 첫 번째
  - 두 번째

5. 링크
  ```
      [링크 텍스트](https://www.naver.com)
  ```
  [네이버로 가기](https://www.naver.com)

6. 이미지
  ```
  ![포스터](http://~~)
  ```
![포스터](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNDAyMjhfMTA4%2FMDAxNzA5MDgzMTM0MzA4.QLPEzhK4CwBRX0CIHPIVkpfvdPi1BvJz-BCWOeGGo3Ig.JSkxHSO_QrklWN7Hzno5epPP68fOxoVww_CmFkeXqrYg.JPEG%2F%25B4%25D9%25BF%25EE%25B7%25CE%25B5%25E5_%25281%2529.jpg&type=sc960_832)

7. 인용구
  
  ```
      > 이것은 인용구 입니다.
      >> 중첩된 인용구 입니다.
  ```

  > 이것은 인용구 입니다.
  >> 중첩된 인용구 입니다.

8. 특정언어의 코드 블록
```markdown

    ```python
        print("hello^^")
    ```
```
```python
    print("hello^^")
```

9. 구분선
```---```
---

10. 체크박스
``` - []할 일 - [x] 완료한 일```

 - [] 할 일
 - [x] 완료한 일

11. 테이블
``` | 제목1 | 제목2 |
    |------|-----|
    | 내용1 | 내용2 |
```
 | 제목1 | 제목2 |
 |------|-----|
 | 내용1 | 내용2 |

 12. 이모지 추가하기

 [이모지 검색 및 다운로드](http://emojipedia.org)

 - 오늘의 날씨는? ☔
 - 나는 오늘 열심히 해서

 13. 배지 추가
 [배지 달기(언어, 기술 개발 도구, 자격)](http://simpleicons.org)


 <img src="<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>3M</title><path d="M18.903 5.954L17.17 13.03l-1.739-7.076h-5.099v2.613C9.72 6.28 7.56 5.706 5.558 5.674 3.12 5.641.563 6.701.469 9.936h3.373c0-.977.747-1.536 1.588-1.523 1.032-.008 1.508.434 1.533 1.124-.036.597-.387 1.014-1.525 1.014H4.303V12.9h1.03c.584 0 1.399.319 1.431 1.155.04.995-.652 1.435-1.501 1.443-1.517-.053-1.763-1.225-1.763-2.23H0c.015.677-.151 5.091 5.337 5.059 2.629.025 4.464-1.085 5.003-2.613v2.342h3.455v-7.632l1.867 7.634h3.018l1.875-7.626v7.634H24V5.954h-5.097zm-8.561 7.06c-.429-.893-1.034-1.284-1.376-1.407.714-.319 1.09-.751 1.376-1.614v3.021z"/></svg>">