<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft2_qibax"/><path class="d6zqoe23a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:navigation-end" /></template>
<style>
.d6zqoe23a {
  fill: currentColor;
  d: path("M11 3.5h2A1.5 1.5 0 0 1 14.5 5v2A1.5 1.5 0 0 1 13 8.5h-2A1.5 1.5 0 0 1 9.5 7V5A1.5 1.5 0 0 1 11 3.5m-5 5h2A1.5 1.5 0 0 1 9.5 10v2A1.5 1.5 0 0 1 8 13.5H6A1.5 1.5 0 0 1 4.5 12v-2A1.5 1.5 0 0 1 6 8.5m10 0h2a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-2A1.5 1.5 0 0 1 16 8.5");
}

.ft2_qibax {
  d: path("M4.5 3v18M6 3.5h12A1.5 1.5 0 0 1 19.5 5v7a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 12V5A1.5 1.5 0 0 1 6 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
