<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="yowus8bnh"/><path class="ytx6pkbfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-worker-sharp" /></template>
<style>
.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yowus8bnh {
  cx: 12px;
  cy: 12.75px;
  r: 2.25px;
}

.ytx6pkbfp {
  d: path("M6.5 21h11.75v-.75c0-1.71-2.81-3-6.25-3s-6.25 1.29-6.25 3V21zM6.25 8.25h11.5M8 8.25a4 4 0 0 1 8 0");
}

</style>
