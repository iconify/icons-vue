<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i2biyzbmj"/><path class="rhi2ieb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:presentation-line" /></template>
<style>
.i2biyzbmj {
  d: path("M2.5 2.5h19V16h-19Zm5.5 19l2-5.5m6 5.5L14 16");
}

.rhi2ieb2n {
  d: path("M6.5 12.5L10 9l3 2l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
