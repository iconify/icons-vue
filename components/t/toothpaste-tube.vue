<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gahg-mb5f"/><path class="ec1wwpvsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toothpaste-tube" /></template>
<style>
.ec1wwpvsj {
  d: path("m16.419 4.752l.708-.707a1.75 1.75 0 0 1 2.474 0l.354.354a1.75 1.75 0 0 1 0 2.474l-.707.708a1.75 1.75 0 0 1-2.475 0l-.354-.354a1.75 1.75 0 0 1 0-2.475M5.106 13.591l5.303 5.303");
}

.gahg-mb5f {
  d: path("m4.324 14.313l9.109-7.347a1.75 1.75 0 0 1 .756-.354l.463-.092a1.68 1.68 0 0 1 1.521.461l.846.846a1.68 1.68 0 0 1 .461 1.521l-.092.463a1.75 1.75 0 0 1-.354.756l-7.347 9.109a1.75 1.75 0 0 1-2.6.139l-2.902-2.902a1.75 1.75 0 0 1 .139-2.6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
