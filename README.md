# Inha Logo

> Inha Univ.’s Logos

아래 로고는 [인하대학교](http://www.inha.ac.kr)를 대표하는 상징입니다.

**각 로고의 저작권은 인하대학교에 있으며 임의로 변경 사용할 수 없습니다.**

또한, 허가 없이 상업적 목적으로 이용하면 법률에 저촉됩니다.

로고의 디자인 가이드라인 및 원본 파일([AI](https://en.wikipedia.org/wiki/Adobe_Illustrator))은 [이곳](http://www.inha.ac.kr/kr/1828/subview.do)을 참고하시길 바랍니다.

## SVG

> Static and Animated Logos

로고의 패스 정리 및 최적화는 수작업으로 이루어졌습니다.

### Static Images

| Symbol Mark                                            | Emblem                                       |
| ------------------------------------------------------ | -------------------------------------------- |
| ![Inha Symbol Mark](./svg/static/inha_symbol_mark.svg) | ![Inha Emblem](./svg/static/inha_emblem.svg) |

| Character Logo A Type                                                 | Character Logo B Type                                                |
| --------------------------------------------------------------------- | -------------------------------------------------------------------- |
| ![Inha Character Logo A Type](./svg/static/inha_character_square.svg) | ![Inha Character Logo B Type ](./svg/static/inha_character_rect.svg) |

| 50th Anniversary Emblem                                            | 55th Anniversary Emblem                                            | 60th Anniversary Emblem                                            |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| ![Inha 50th Anniversary Emblem](./svg/static/inha_50th_emblem.svg) | ![Inha 55th Anniversary Emblem](./svg/static/inha_55th_emblem.svg) | ![Inha 60th Anniversary Emblem](./svg/static/inha_60th_emblem.svg) |

### Animated Images

각 로고의 애니메이션은 임의로 넣은 것이며, 인하대학교에서 배포된 애니메이션이 아님을 밝힙니다.

애니메이션을 위해 삽입된 [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)는 [MIT 라이선스](./LICENSE)를 따릅니다.

| Symbol Mark                                             | Emblem                                        |
| ------------------------------------------------------- | --------------------------------------------- |
| ![Inha Symbol Mark](./svg/animate/inha_symbol_mark.svg) | ![Inha Emblem](./svg/animate/inha_emblem.svg) |

| Character Logo A Type                                                  | Character Logo B Type                                                 |
| ---------------------------------------------------------------------- | --------------------------------------------------------------------- |
| ![Inha Character Logo A Type](./svg/animate/inha_character_square.svg) | ![Inha Character Logo B Type ](./svg/animate/inha_character_rect.svg) |

| 50th Anniversary Emblem                                             | 55th Anniversary Emblem                                             | 60th Anniversary Emblem                                             |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| ![Inha 50th Anniversary Emblem](./svg/animate/inha_50th_emblem.svg) | ![Inha 55th Anniversary Emblem](./svg/animate/inha_55th_emblem.svg) | ![Inha 60th Anniversary Emblem](./svg/animate/inha_60th_emblem.svg) |

## Vue

> Logo Components for [Vue.js](https://vuejs.org/)

Vue.js 컴포넌트로 제공되는 로고입니다.

```vue
<template>
  <div>
    <inha-emblem />
    <inha-symbol-mark />
  </div>
</template>

<script>
import InhaEmblem from './InhaEmblem.vue';
import InhaSymbolMark from './InhaSymbolMark.vue';

export default {
  components: {
    InhaEmblem,
    InhaSymbolMark
  }
};
</script>
```

### [Symbol Mark](./vue/InhaSymbolMark.vue)

```html
<inha-symbol-mark theme="black" size="48px" />
```

#### Properties

- theme: 로고 색상(`black`/`blue`/`gray`/`gold`/`sky`/`white`)
- size: 로고 크기(default: `"192px"`)

### [Emblem](./vue/InhaEmblem.vue)

```html
<inha-emblem theme="black" size="48px" />
```

#### Properties

- theme: 로고 색상(`black`/`blue`/`gray`/`gold`/`sky`/`white`)
- size: 로고 크기(default: `"192px"`)
