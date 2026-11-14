<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0wsz5bye"/><path class="p5lzv-bvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mode-video" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p5lzv-bvu {
  d: path("M5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m10.829 5.585l3-1.5A1.5 1.5 0 0 1 21 12.927v5.146a1.5 1.5 0 0 1-2.171 1.342l-3-1.5A1.5 1.5 0 0 1 15 16.573v-2.146a1.5 1.5 0 0 1 .829-1.342M8.5 7.5h.01");
}

.r0wsz5bye {
  d: path("M5.625 11h6.75A2.625 2.625 0 0 1 15 13.625v3.75A2.625 2.625 0 0 1 12.375 20h-6.75A2.625 2.625 0 0 1 3 17.375v-3.75A2.625 2.625 0 0 1 5.625 11");
}

</style>
