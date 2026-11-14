<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y2oavfbig"/><path class="u4lotsbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safe" /></template>
<style>
.u4lotsbrd {
  d: path("M7.5 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm10-2v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y2oavfbig {
  d: path("M3 3.5h18v16H3Zm3.5 16V21m11-1.5V21");
}

</style>
