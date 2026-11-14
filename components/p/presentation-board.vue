<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezka2rber"/><path class="wz6_99bsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:presentation-board" /></template>
<style>
.ezka2rber {
  d: path("M3 3h18v12H3Zm5 12l-2 6.5M16 15l2 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wz6_99bsl {
  d: path("m6.5 11.5l3.5-3l3 1.5l4.5-4");
}

</style>
