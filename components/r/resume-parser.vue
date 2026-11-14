<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azg1xbbrq"/><path class="no2cj_fzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:resume-parser" /></template>
<style>
.azg1xbbrq {
  d: path("M4 2.5h3.75L10 4.75V21.5H2.5V4A1.5 1.5 0 0 1 4 2.5Zm14.25 0h3.25V7h-3.25Zm0 7.25h3.25v4.5h-3.25Zm0 7.25h3.25v4.5h-3.25Z");
}

.no2cj_fzq {
  d: path("M7.75 2.5v2.25H10M5.25 9.5h2m-2 3h2m-2 3h2m5.5-10.75h2.75M14.25 3.5l1.25 1.25L14.25 6m-1.5 6h2.75m-1.25-1.25L15.5 12l-1.25 1.25m-1.5 6h2.75M14.25 18l1.25 1.25l-1.25 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
