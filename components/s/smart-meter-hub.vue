<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wec5fbbnn"/><path class="jahc6pb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-meter-hub" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jahc6pb1g {
  d: path("M7.25 12h3.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 7.25 12M5.5 18.5H9m6.5-13a3 3 0 0 1 3 3m-3-6a6 6 0 0 1 6 6");
}

.wec5fbbnn {
  d: path("M6.875 9h4.25a4.375 4.375 0 0 1 4.375 4.375v3.75a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 2.5 17.125v-3.75A4.375 4.375 0 0 1 6.875 9");
}

</style>
