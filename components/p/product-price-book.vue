<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hv9kgw6dy"/><path class="z6m01vbxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:product-price-book" /></template>
<style>
.hv9kgw6dy {
  d: path("M21 12.567V4.5q-6-.75-9 1.5q-3-2.25-9-1.5v14q5.497-.687 8.475 1.144M12 6v5.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6m01vbxe {
  d: path("M14.25 14.25h4.5L22 17.5L17.5 22l-3.25-3.25Z");
}

</style>
