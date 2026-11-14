<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="moser-b7x"/><path class="i9_wgoeyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skeleton-sled" /></template>
<style>
.i9_wgoeyd {
  d: path("M2.5 16h15.75a3 3 0 0 0 0-6M6 12v4m6-4v4");
}

.moser-b7x {
  d: path("M3 8h12v4H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
