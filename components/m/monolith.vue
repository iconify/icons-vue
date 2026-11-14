<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rot9v-wqs"/><path class="qz_bnctsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monolith" /></template>
<style>
.qz_bnctsg {
  d: path("m5 6l3.5-3.5H19V18l-3.5 3.5m0-15.5L19 2.5");
}

.rot9v-wqs {
  d: path("M5 6h10.5v15.5H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
