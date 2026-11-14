<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qr3z9nnzx"/><path class="s8l_c9bns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:red-giant" /></template>
<style>
.qr3z9nnzx {
  d: path("M5.5 11a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

.s8l_c9bns {
  d: path("M11.875 15.464a4.75 4.75 0 0 1-2.839-6.089M4 20.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
