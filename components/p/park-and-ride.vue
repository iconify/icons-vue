<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wwl5xrb2r"/><path class="qyc5wgb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:park-and-ride" /></template>
<style>
.qyc5wgb4z {
  d: path("M5.25 5.25h6.5v5h-6.5Zm.5 8.75h.01m5.49 0h.01m6.24 7.75V15h2a2.25 2.25 0 0 1 0 4.5h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwl5xrb2r {
  d: path("M2.5 2.5h12v15h-12Zm3 15V20m6-2.5V20");
}

</style>
