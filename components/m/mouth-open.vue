<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m8uf88jxd"/><path class="reyug-xyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouth-open" /></template>
<style>
.m8uf88jxd {
  d: path("M2.5 12.5a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0ZM3.75 9h16.5M9.5 5.75V9m5-3.25V9M4.25 16.5h15.5m-9.75 0v2.75m4-2.75v2.75");
}

.reyug-xyv {
  d: path("M8 16.5c0-3.75 8-3.75 8 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
