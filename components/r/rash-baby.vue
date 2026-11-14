<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ysirmiopq"/><path class="y7bmx5b1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rash-baby" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7bmx5b1f {
  fill: currentColor;
  d: path("M2.5 4.75h2v3.5h-2Zm17 0h2v3.5h-2ZM7.25 11a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm2.5-1a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm.75 2.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0ZM8.75 14.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

.ysirmiopq {
  d: path("M3.5 5.5h17V10c-3.25.5-5.5 3.5-6 8.5h-5c-.5-5-2.75-8-6-8.5Zm0 2.5h17");
}

</style>
