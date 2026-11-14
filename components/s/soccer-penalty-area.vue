<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dp2lo8_bx"/><path class="f1wolacea"/><path class="xkoa3sbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-penalty-area" /></template>
<style>
.dp2lo8_bx {
  d: path("M2.5 19.5v-17h19v17");
}

.f1wolacea {
  d: path("M6 2.5V12h12V2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xkoa3sbkw {
  d: path("M9 2.5v3.25h6V2.5m-3 6.25h.01M9 12a3 3 0 0 0 6 0");
}

</style>
