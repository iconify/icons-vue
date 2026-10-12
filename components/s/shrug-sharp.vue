<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ckdeowbwc"/><path class="cx77jfbqf"/><path class="dsd-7lbgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shrug-sharp" /></template>
<style>
.ckdeowbwc {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
}

.cx77jfbqf {
  d: path("M7.5 21.25h-1v-3.5a5.5 5.5 0 0 1 11 0v3.5h-1Z");
}

.dsd-7lbgn {
  d: path("M6.75 16L4 17l-1-2.5M17.25 16L20 17l1-2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
