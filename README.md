# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장 (Paragraph)

동해물과 백두산이 마르고 닳고록 
하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Breaks) 띄어쓰기 2번/br

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조 (Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록 (List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크 (Link)

<a  href="http://google.com">GOOGLE</a>

[GOOGLE](http://google.com)

<a  href="http://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](http://naver.com "NAVER로 이동!")

<a  href="http://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지 (Image)

이미지 하나  
![HEROPY](https://heropy.blog/css/images/logo.png)

이미지와 링크
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

>> 중첩된 인용문
>>>중중첩된 인용문 1
>>>중중첩된 인용문 2
>>>중중첩된 인용문 3

# 인라인 (Inline) 코드강조

CSS 에서 'background' 혹은  
'background-image' 속성으로 요소에  
배경 이미비를 삽입할 수 있습니다.

# 블록 (Block) 코드강조

```html
<a  href="http://google.com" target="_blank">GOOGLE</a>
```

```css
.list >li {
  position : absolut;
  top: 40px;
}
```

```javascript
function func() {
  var a + 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
코딩이 참 쉽다.
```

# 표 (Table)

position 속성

값 | 의미 | 기본값  
-- | :--: | --:
static | 기준없음  | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML)
##### markdown 문법에 HTML 문법을 사용하는 것

<br/>
동해물과 <u>백두산이</u>
<span style="text-decoration: underline;">마르고</span> 닳고록<br/>
하느님이 보우하사 우리나라 만세

<a href="http://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

# 수평선 (Horizontal Rule)

___

---

***