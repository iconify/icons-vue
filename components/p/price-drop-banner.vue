<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="me7z-dben"/><path class="qmtcpccsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:price-drop-banner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.me7z-dben {
  d: path("M2.5 2.5h19M8.813 6h6.374a2.625 2.625 0 0 1 2.331 3.831l-3.186 6.161a2.625 2.625 0 0 1-4.664 0L6.482 9.831A2.625 2.625 0 0 1 8.813 6M7 2.5V6m10-3.5V6m-5 2.75V14");
}

.qmtcpccsb {
  d: path("M9.75 11.75L12 14l2.25-2.25");
}

</style>
