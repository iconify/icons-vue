<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dl95iz3wi"/><circle class="keov1bbdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wheelbarrow-sharp" /></template>
<style>
.dl95iz3wi {
  d: path("M4.5 7.75h16.25l-.62 1.09l-2.76 4.82l-.62 1.09h-9.5l-.62-1.09l-2.76-4.82l-.62-1.09zm.25 0L2.75 5m5.5 9.75l-.75 5.5");
}

.keov1bbdj {
  cx: 14px;
  cy: 17.5px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
