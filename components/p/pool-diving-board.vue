<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7r9mjrnv"/><path class="by8bomzag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pool-diving-board" /></template>
<style>
.by8bomzag {
  d: path("M4.564 9H5.87a1.5 1.5 0 0 1 1.495 1.625l-.75 9A1.5 1.5 0 0 1 5.12 21h-.181a1.5 1.5 0 0 1-1.499-1.438l-.375-9A1.5 1.5 0 0 1 4.564 9M10 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 8q2-1.5 4 0t4 0t3.5-.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7r9mjrnv {
  d: path("M3.75 6.5h12.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 16.25 9H3.75A1.25 1.25 0 0 1 2.5 7.75A1.25 1.25 0 0 1 3.75 6.5");
}

</style>
