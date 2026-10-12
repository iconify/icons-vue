<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zs03pvqjv"/><path class="l-3l-1bjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rivet-gun-sharp" /></template>
<style>
.l-3l-1bjd {
  d: path("M14.5 8.25H17l.31.95l3.13 9.6l.31.95l-.95.32l-1.1.36l-.95.32l-.32-.95l-3.61-10.6l-.32-.95zm-4.25 0l4 12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zs03pvqjv {
  d: path("M8.5 3.75h12.75v4.5H8.5zm-.49 1.08l-2.02.34l-.49.08v1.5l.49.08l2.02.34l.49.08v-2.5zM2.75 6H5.5");
}

</style>
