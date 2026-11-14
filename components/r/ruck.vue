<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxo540bxa"/><path class="tul42lb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ruck" /></template>
<style>
.dxo540bxa {
  d: path("M2.5 16v-1.5a3 3 0 0 1 6 0a3.5 3.5 0 0 1 7 0a3 3 0 0 1 6 0V16m-18-9.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.25-2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm6.75 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 20h19");
}

.tul42lb0f {
  d: path("M8.75 18.5q3.25-3 6.5 0q-3.25 3-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
