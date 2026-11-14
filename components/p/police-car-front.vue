<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnc43m90h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:police-car-front" /></template>
<style>
.nnc43m90h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 12l1.25-4c.25-.9 1-1.5 2-1.5h6.5c1 0 1.75.6 2 1.5l1.25 4M3 12h18v6.5H3Zm3 6.5V21m12-2.5V21M6.75 15.25h.01m10.49 0h.01M10 2h4v1.75h-4Zm.5 13.5h3");
}

</style>
