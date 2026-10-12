<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cx6qiacja"/><circle class="xr52llboc"/><path class="o042cdc7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scarecrow-sharp" /></template>
<style>
.cx6qiacja {
  d: path("M7.75 5.25h8.5m-6.25 0l.5-2.5h3l.5 2.5");
}

.o042cdc7l {
  d: path("M2.75 14.5h18.5m-11.95 0h6.2l-.09.8l-.32 2.9l-.09.8H9l-.09-.8l-.32-2.9l-.09-.8zM12 19v2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xr52llboc {
  cx: 12px;
  cy: 9.75px;
  r: 1.75px;
}

</style>
