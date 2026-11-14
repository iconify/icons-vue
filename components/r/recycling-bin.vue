<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="loklsz4ly"/><path class="ercvg2asw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recycling-bin" /></template>
<style>
.ercvg2asw {
  d: path("m13 8.75l3.25 6l.25-2m-1.25 3.75h-6.5l1.5 1.25m-2.5-3l3.25-6l-1.75.75");
}

.loklsz4ly {
  d: path("M3 3.5h18m-16.5 0V19a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
