# Y이드스트릿체

[배포처 바로가기](https://www.yspotlight.co.kr/brand/font?tabNo=1)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Ydestreet`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'Ydestreet';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Light.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Light.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Light.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Ydestreet';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/Ydestreet-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/subsets/Ydestreet-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/Ydestreet/subsets/Ydestreet-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Ydestreet", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
• Y이드스트릿체의 지식재산권은 |주|케이티에 있다. 
• Y이드스트릿체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며, 폰트 사용자에 의한 재배포 또한 가능하다. 단, 폰트 파일의 수정 및 유료 판매는 금지한다. 
• Y이드스트릿체는 인쇄, 웹, 영상, 임베딩, 패키지 등에 상업적 목적으로 사용이 가능하다. 단, BI/CI 용도로는 사용을 금지한다.
```
