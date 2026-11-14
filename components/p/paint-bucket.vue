<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jz0d_uhtt"/><path class="isvd49b0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:paint-bucket" /></template>
<style>
.isvd49b0q {
  d: path("M5 12q3.5-1.5 7 0t7 0");
}

.jz0d_uhtt {
  d: path("M4.5 8h15L18 20.5a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Zm0 0a7.5 5.5 0 0 1 15 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
