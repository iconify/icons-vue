<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d90oeycoz"/><path class="cnwhnbbmh"/><path class="ub1mcfbjy"/><path class="v90yymbhv"/><path class="yy6mapbcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-to-text-outline-thin" /></template>
<style>
.cnwhnbbmh {
  d: path("M11 13a4 4 0 0 1 -8 0");
}

.d90oeycoz {
  d: path("M4 7a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ub1mcfbjy {
  d: path("M14 9h7");
}

.v90yymbhv {
  d: path("M14 14h7");
}

.yy6mapbcz {
  d: path("M14 19h4");
}

</style>
