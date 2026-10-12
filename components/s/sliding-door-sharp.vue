<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nebn4omje"/><path class="ln-c5bwso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sliding-door-sharp" /></template>
<style>
.ln-c5bwso {
  d: path("M14.5 12H18m-1.5-1.5L18 12l-1.5 1.5");
}

.nebn4omje {
  d: path("M3.75 2.75h16.5v18.5H3.75zm8.25 0v18.5M9.25 10.5v3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
