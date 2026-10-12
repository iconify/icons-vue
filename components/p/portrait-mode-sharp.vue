<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w34_6db1d"/><circle class="drtvz1btn"/><path class="ygyw9ob-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:portrait-mode-sharp" /></template>
<style>
.drtvz1btn {
  cx: 12px;
  cy: 8.5px;
  r: 2.25px;
}

.w34_6db1d {
  d: path("M4.75 8V3.75H9m6 0h4.25V8m0 8v4.25H15m-6 0H4.75V16");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygyw9ob-w {
  d: path("M7.75 17.5a4.25 4.25 0 0 1 8.5 0Z");
}

</style>
