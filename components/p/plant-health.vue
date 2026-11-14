<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g1623gbcr"/><path class="tsfzewb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-health" /></template>
<style>
.g1623gbcr {
  d: path("M3.5 20.5c0-11.5 5.5-17 17-17c0 11.5-5.5 17-17 17Z");
}

.tsfzewb-o {
  d: path("M12 15s-2.75-1.75-2.75-3.75c0-1 .75-1.75 1.75-1.75c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c1 0 1.75.75 1.75 1.75c0 2-2.75 3.75-2.75 3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
