<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="snmw-kbzf"/><circle class="zoz2euh6v"/><path class="gtcrd1b4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunscreen-sharp" /></template>
<style>
.gtcrd1b4v {
  d: path("M17 3v1m0 6.5v1m3.25-4.25h1");
}

.snmw-kbzf {
  d: path("M4 2.75h7.75l-.12 1.24l-1.01 11.02l-.12 1.24H4l-.12-1.24L2.87 3.99l-.12-1.24zm.75 13.5h5v5h-5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zoz2euh6v {
  cx: 17px;
  cy: 7.25px;
  r: 1.75px;
}

</style>
