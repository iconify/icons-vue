<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqa0qqbzw"/><path class="no2cj_fzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:resume-parser" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.no2cj_fzq {
  d: path("M7.75 2.5v2.25H10M5.25 9.5h2m-2 3h2m-2 3h2m5.5-10.75h2.75M14.25 3.5l1.25 1.25L14.25 6m-1.5 6h2.75m-1.25-1.25L15.5 12l-1.25 1.25m-1.5 6h2.75M14.25 18l1.25 1.25l-1.25 1.25");
}

.wqa0qqbzw {
  d: path("M4 2.5h3.75L10 4.75V21.5H2.5V4A1.5 1.5 0 0 1 4 2.5m15.75 0H20A1.5 1.5 0 0 1 21.5 4v1.5A1.5 1.5 0 0 1 20 7h-.25a1.5 1.5 0 0 1-1.5-1.5V4a1.5 1.5 0 0 1 1.5-1.5m0 7.25H20a1.5 1.5 0 0 1 1.5 1.5v1.5a1.5 1.5 0 0 1-1.5 1.5h-.25a1.5 1.5 0 0 1-1.5-1.5v-1.5a1.5 1.5 0 0 1 1.5-1.5m0 7.25H20a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-.25a1.5 1.5 0 0 1-1.5-1.5v-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
