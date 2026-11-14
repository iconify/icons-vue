<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ig3ajobdn"/><path class="ijla-ebtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:powder-packet" /></template>
<style>
.ig3ajobdn {
  d: path("m5 5l1.75-2L8.5 5l1.75-2L12 5l1.75-2l1.75 2l1.75-2L19 5v14a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 19Zm0 3h14");
}

.ijla-ebtb {
  d: path("M8 17.5q4-6 8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
