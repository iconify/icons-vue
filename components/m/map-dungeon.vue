<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mey21abvb"/><path class="o0za0bc4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-dungeon" /></template>
<style>
.mey21abvb {
  d: path("m3 5l6-2l6 2l6-2v16l-6 2l-6-2l-6 2Z");
}

.o0za0bc4z {
  d: path("M8 16.25V13.5a4 4 0 0 1 8 0v2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
