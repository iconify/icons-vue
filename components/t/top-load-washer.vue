<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p3ndogbwf"/><path class="otnq2sbmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:top-load-washer" /></template>
<style>
.otnq2sbmz {
  d: path("M8.5 15.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.p3ndogbwf {
  d: path("m3.5 9l2-6.5h13l2 6.5v10.5a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2Zm0 0h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
