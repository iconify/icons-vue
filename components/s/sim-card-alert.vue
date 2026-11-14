<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sev6wc-1s"/><path class="yyh-gbbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sim-card-alert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sev6wc-1s {
  d: path("M5 2.5h6.5L15 6v11a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 17V4A1.5 1.5 0 0 1 5 2.5");
}

.yyh-gbbav {
  d: path("M8 8.5h2a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 10 14.5H8a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 8 8.5m10 6V18m0 3h.01");
}

</style>
