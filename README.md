# 인피니티산스

[배포처 바로가기](https://www.wemade.com/Company/Ci)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Infinity Sans`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Infinity Sans';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-Regular.otf') format('opentype');
}
@font-face {
    font-family: 'Infinity Sans';
    font-weight: 600;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-Bold.otf') format('opentype');
}
@font-face {
    font-family: 'Infinity Sans';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-ExtraBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-ExtraBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/InfinitySans-ExtraBold.otf') format('opentype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/subsets/InfinitySans-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/InfinitySans/subsets/InfinitySans-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Infinity Sans", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
‘인피니티 산스(Infinity Sans)’의 지식재산권은 ㈜위메이드(www.wemade.com)에 있습니다. 
 
위메이드는 ‘인피니티 산스’를 개인 및 기업을 포함한 모든 사용자에게 무료로 제공합니다. 단, 대한민국 외에서 ‘인피니티 산스’를 다운받거나 사용하고자 하는 경우 반드시 당사의 사전 허락을 받아야 하며, 당사의 사전 허락 없이 대한민국 외에서의 복제 및 사용은 허락되지 않습니다. 
 
위메이드는 ‘인피니티 산스’ 소프트웨어를 저작권, 특허권, 상표권 및 기타 권리의 비침해성과 특정 목적에 적합성을 포함한 명시적, 묵시적인 어떠한 종류의 보증 없이 ‘있는 그대로’ 제공합니다. 
 
위메이드는 ‘인피니티 산스’ 글꼴 자체를 유료로 판매하는 것을 금지합니다. 또한, 임의 수정 및 2차 가공에 의한 재배포를 할 수 없으며, 배포되는형태 그대로 사용해야 합니다. 특히, 어떠한 경우에도 위메이드는 ‘인피니티 산스’의 사용 또는 이의 사용불가, 그 밖에 서체 소프트웨어의 취급과 관련하여 발생하는 모든 계약, 불법행위 혹은 다른 일로 하여금 발생하는 일반적, 특수적, 간접적, 부차적 혹은 필연적 손해를 포함하는 소송, 손해 혹은 기타 책임에 대한 의무를 일체 부담하지 않습니다. 
 
위메이드는 ‘인피니티 산스’ 출처 표기를 권장합니다. 또한, ‘인피니티 산스’를 사용한 인쇄물, 광고물(온라인 포함)의 이미지는 위메이드 및 계열사 프로모션을 위해 활용될 수 있으며, ‘인피니티 산스’ 사용 시 이러한 활용에 동의하는 것으로 간주합니다. 위메이드는 언제든지 본 라이선스와 다른 조건으로 서체 사용을 허락하거나 서체의 배포를 중단시킬 수 있는 권리를 보유합니다. 
 
이를 원치 않는 사용자는 언제든지 당사에 협의를 요청하실 수 있습니다. 
```
