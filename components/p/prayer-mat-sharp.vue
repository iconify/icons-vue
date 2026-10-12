<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rjvr_89gq"/><path class="nwx4x4x0g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prayer-mat-sharp" /></template>
<style>
.nwx4x4x0g {
  d: path("M8.5 16.75V11a3.5 3.5 0 0 1 7 0v5.75");
}

.rjvr_89gq {
  d: path("M5 4.25h14v15.5H5zm2.5-1.5v1.5m3-1.5v1.5m3-1.5v1.5m3-1.5v1.5m-9 15.5v1.5m3-1.5v1.5m3-1.5v1.5m3-1.5v1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
