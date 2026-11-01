---
version: "1.0"
name: "{서비스 이름}"
description: "{디자인 인상 한 줄}"
source: "{공개 문서 | 관찰(앱 캡처) | 관찰(웹 computed style)}"
updated: "YYYY-MM-DD"
license: "CC BY 4.0"
attribution: "SylviaLab DESIGN.md (https://github.com/sylviagithubhj/sylvialab-design-md) · CC BY 4.0"

colors:
  primary: "#000000"
  on-primary: "#ffffff"
  surface: "#ffffff"
  text-primary: "#000000"
  text-secondary: "#666666"
  border: "#e5e5e5"
  danger: "#e5484d"

typography:
  title-lg:
    fontFamily: "Pretendard, -apple-system, sans-serif"
    fontSize: 22px
    fontWeight: 700
    lineHeight: 1.36
  body:
    fontFamily: "Pretendard, -apple-system, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.5

rounded:
  sm: 4px
  md: 8px
  full: 9999px

spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    height: 48px
---

# {서비스 이름} 디자인 시스템

> 근거: {공개 문서 기반 | 관찰 기반 (실측일, 기기·화면)}
> 작성: SylviaLab · 최종 수정 YYYY-MM-DD
> 라이선스: CC BY 4.0 · 다시 쓰거나 고쳐 쓸 때 출처를 꼭 남겨 주세요 → SylviaLab DESIGN.md (https://github.com/sylviagithubhj/sylvialab-design-md)

이 문서는 디자인 시스템의 다섯 층(원칙, 토큰, 컴포넌트, 사용 규칙, 구현·검증)을 한 파일로 줄인 요약이다. 맨 위 YAML은 도구와 AI가 그대로 읽는 값이고, 아래 글은 그 값을 언제·왜 쓰는지 설명한다.

## 1. 개요와 원칙
- 서비스 성격: 
- 디자인 인상 한 줄: 
- 공식 시스템 이름: (없으면 "공개된 이름 없음")
- 디자인 원칙 3~5개: 공식 원칙이면 출처를 달고, 관찰에서 읽은 원칙이면 "(관찰에서 정리)"라고 적는다.
  1. 
  2. 
  3. 
- 톤: 한 문장 (예: 차분하고 신뢰감 있게, 정보 밀도보다 가독성)

### 특장점
이 디자인 시스템만의 강점 3~5개. 각 줄은 "무엇이 다른가 — 근거(값·화면·컴포넌트)" 꼴로, 숫자나 색·컴포넌트 이름이 들어가야 한다. 일반론(깔끔하다, 일관적이다)은 쓰지 않는다.
- 
- 
- 

### 배울 점
다른 제품이 가져다 쓸 만한 해법 2~3개. "○○할 때 ○○처럼 한다" 꼴.
- 

## 2. 색상
의미(역할) 이름의 토큰과 실제 값을 함께 적는다. 표 머리는 `| 토큰 | HEX | 쓰임 |`.

### 브랜드·행동
| 토큰 | HEX | 쓰임 |
|---|---|---|

### 바탕·선
| 토큰 | HEX | 쓰임 |
|---|---|---|

### 글자
| 토큰 | HEX | 쓰임 |
|---|---|---|

### 상태
| 토큰 | HEX | 쓰임 |
|---|---|---|

### 색 사용 규칙
- primary는 ○○에만 쓴다.
- danger는 삭제·경고에만 쓴다.

## 3. 타이포그래피
- 글꼴: {이름}(근거)
- 대체 글꼴: 

| 단계 | 크기(pt) | 굵기 | 행간 | 쓰임 |
|---|---|---|---|---|

### 글자 사용 규칙
- 

## 4. 레이아웃·간격
- 기준 화면: 
- 화면 좌우 여백: 
- 간격 단계(관찰, pt): 4, 8, 12, 16, 24
- 그리드·최대 폭: 

### 간격 적용 규칙
- 

## 5. 모서리·고도·모션
| 토큰 | 값 | 쓰임 |
|---|---|---|

- 고도(그림자·층): 
- 모션(길이·이징): 

## 6. 컴포넌트
컴포넌트마다 변형, 상태, 쓰는 때, 쓰지 않는 때를 적는다. 보지 못한 상태는 `확인 필요`.

### 버튼
| 변형 | 모양 | 쓰는 때 |
|---|---|---|

- 상태: 기본 / 눌림 / 비활성 / 로딩
- 쓰지 않는 때: 

### 입력창
### 칩·탭
### 카드·리스트
### 상단 바·하단 탭 바
### 바텀시트·모달
### 토스트·배지

## 7. 패턴
반복되는 화면 해법을 적는다.
- 목록 → 상세: 
- 검색: 
- 빈 상태·오류: 
- 폼·결제: 

## 8. 접근성
- 글자 대비(WCAG 2.x, 계산값):

| 글자 | 바탕 | 대비 | 본문 기준 4.5:1 |
|---|---|---|---|

- 터치 영역: 
- 최소 글자 크기: 
- 포커스·스크린리더·글자 확대: 

## 9. 글쓰기 톤
- 말투: 
- 버튼 문구 꼴: 
- 숫자·단위 표기: 

## 10. Do & Don't
관찰 기반 문서의 규칙은 "이 서비스 화면에서 반복되는 규칙"을 SylviaLab이 정리한 것이다(공식 규칙 아님).

### Do
- 
### Don't
- 

## 11. 구현·운영
- 코드 컴포넌트·패키지: 
- Figma 라이브러리: 
- 문서·Storybook: 
- 버전·변경 관리: 
(공개 자료에서 확인한 것만 적고, 없으면 "공개 자료 없음")

## 12. AI에 넣을 때
```
{서비스} 스타일로 디자인해 줘.
- 
```

## 13. 참고 자료
- {URL 또는 캡처 설명} (확인 YYYY-MM-DD)

근거와 한계
- 
