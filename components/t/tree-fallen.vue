<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xkfcvn5vx"/><path class="ji8z5lbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tree-fallen" /></template>
<style>
.ji8z5lbem {
  d: path("M15 10.5a3 4 0 1 0 6 0a3 4 0 1 0-6 0Zm3 0h.01M5 8.5L2.5 7M5 12.5L2.5 14m0 4h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xkfcvn5vx {
  d: path("M18 6.5H6.5A1.5 1.5 0 0 0 5 8v5a1.5 1.5 0 0 0 1.5 1.5H18");
}

</style>
