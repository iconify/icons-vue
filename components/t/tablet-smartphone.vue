<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r7wtebb_b"/><path class="zzhq_cpmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tablet-smartphone" /></template>
<style>
.r7wtebb_b {
  d: path("M11.5 21.5H5A2.5 2.5 0 0 1 2.5 19V5A2.5 2.5 0 0 1 5 2.5h9A2.5 2.5 0 0 1 16.5 5v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zzhq_cpmg {
  d: path("M14.5 9.5h7v12h-7ZM6 18h2.5m8.75.75h1.5");
}

</style>
