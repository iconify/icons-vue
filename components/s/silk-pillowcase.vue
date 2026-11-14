<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z79145zym"/><path class="h12s2sstn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:silk-pillowcase" /></template>
<style>
.h12s2sstn {
  d: path("M8 14.25Q10.5 11 15 10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z79145zym {
  d: path("M3 5.5q9 2.5 18 0q-2 6.5 0 13q-9-2.5-18 0q2-6.5 0-13Z");
}

</style>
