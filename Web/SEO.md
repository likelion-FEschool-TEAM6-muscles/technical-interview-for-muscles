## 검색 엔진 최적화(Search Engine Optimization)?

- 검색엔진에서 사이트가 빠르게 상위에 노출될 수 있도록 해주는 방법을 웹사이트에 적용하는 것
- 인터넷과 웹 기술 발전에 따라 웹서버에는 수 많은 정보가 저장되어 있어, 빠르게 좋은 정보를 얻는 것이 중요함 (광고와 연계된 경우 금적적인 기회와도 밀접)

## 구글 검색 자동 방식

#### 1. 웹 크롤링

- 막대한 수의 컴퓨터로 수십 억 개의 웹페이지를 탐색하는 과정
- 사용 프로그램 이름: 구글봇, 로봇, 크롤러, 스파이더 등 (다음은 daum, naver는 yeti)

#### 2. 색인 생성 (indexing)

- 발견된 웹 페이지 내용 분석하는 과정
- 텍스트 콘텐츠, 주요 콘텐츠 태그, 속성값(alt, title 등)을 통해 분석하고 삽입된 이미지와 동영상 파일의 목록을 작성하여 페이지 파악
- 최종적으로 정보들은 DB에 저장

#### 3. 순위가 반영된 검색 결과 제공

- 검색 엔진 내부 알고리즘이 가장 관련성 있는 답변을 사용자 위치, 언어, 기기 환경 등 고려하여 적절한 답안을 제시

## 쉽게 적용할 수 있는 SEO 5가지 방법

#### 1. `<title>`태그로 페이지 제목 정하기

#### 2. `description meta tag` 활용 (페이지마다 중복 없이 고유한 설명 사용해야 함)

```html
<head>
     
  <meta
    name="description"
    content="에어비앤비에서 세계 곳곳의 휴가용 임대 숙소, 통나무집, 비치 하우스, 독특한 숙소 및 체험을 찾아보세요. 호스트 분들이 있기에 가능합니다."
  />
</head>
```

#### 3. 제목 태그 (h1~h6)로 중요한 텍스트 강조

- 콘텐츠 계층 구조를 만들어 쉽게 탐색 가능

#### 4. 의미있는 링크 텍스트 작성하기

- `<a>` 태그의 텍스트를 의미
- 링크 텍스트를 일반 텍스트처럼 보이게 하는 CSS 지양

#### 4-1. The Open Graph Protocal

- 링크를 타고 들어가면, 일종의 투표처럼 알고리즘에 영향을 줌 > SNS 는 트래픽을 유발하기 좋은 수단인데, 이때 보기 좋은 링크를 만들어주는 것이 open graph protocal

```html
<meta property="og:title" content="페이지 제목" />
<meta property="og:type" content="컨텐츠 타입" />
<meta property="og:url" content="페이지 주소" />
<meta property="og:image" content="페이지 썸네일 이미지 주소" />
<meta property="og:description" content="페이지 설명" />
```

#### 5. SEO에 좋은 `<img>`태그 활용

- 간단한 alt 속성 사용 (alt는 앵커 텍스트를 대체하기 때문에,함께 사용할 경우 앵커 태그 텍스트는 생략)
- `imgae1.jpg`, `1.png`같은 일반적인 텍스트, 너무 긴 텍스트 등으로 이미지 파일 이름으로 사용하지 않기