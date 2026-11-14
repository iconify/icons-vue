<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wtr_-nbag"/><path class="wke9yzb1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wall-bay" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wke9yzb1e {
  d: path("M8 8h1a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 9 12H8a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 8 8m6.5 1H16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 16 12h-1.5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 14.5 9M9 14.5h.5A1.5 1.5 0 0 1 11 16v1.5A1.5 1.5 0 0 1 9.5 19H9a1.5 1.5 0 0 1-1.5-1.5V16A1.5 1.5 0 0 1 9 14.5m5.5 1H16a1.5 1.5 0 0 1 1.5 1.5v.5A1.5 1.5 0 0 1 16 19h-1.5a1.5 1.5 0 0 1-1.5-1.5V17a1.5 1.5 0 0 1 1.5-1.5");
}

.wtr_-nbag {
  d: path("M6 6h12a1.5 1.5 0 0 1 1.5 1.5v10A1.5 1.5 0 0 1 18 19H6a1.5 1.5 0 0 1-1.5-1.5v-10A1.5 1.5 0 0 1 6 6M5 2.5h14A1.5 1.5 0 0 1 20.5 4v.5A1.5 1.5 0 0 1 19 6H5a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 5 2.5M5.75 19h12.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H5.75a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5.75 19M2.5 12h19m-19 7h19");
}

</style>
