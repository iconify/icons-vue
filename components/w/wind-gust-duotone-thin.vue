<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p0v1mxbfy"/><path class="fx63l30wc"/><path class="fwdv-5bbe"/><path class="j5qohtzrk"/><path class="ae-e09b3w"/><path class="f-g2d4bkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-gust-duotone-thin" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.f-g2d4bkj {
  d: path("M8 17h10");
}

.fwdv-5bbe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 17h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fx63l30wc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5qohtzrk {
  d: path("M6 7h10");
}

.p0v1mxbfy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
