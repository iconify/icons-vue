<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vmvu5zdno"/><path class="l9v20jr1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermometer-ear-sharp" /></template>
<style>
.l9v20jr1n {
  d: path("M10.5 8.25H15v1h-5v-1z");
}

.vmvu5zdno {
  d: path("m3.44 8.46l3.37-1.42Q7.5 6.75 8 6.38L8.5 6h9.25l.53.53l.69.69l.53.53v1q0 .75-.03 1.5l-.44 10.25l-.03.75h-3.25l-.04-.75l-.42-8.25l-.04-.75H8.5l-.5-.37q-.5-.38-1.19-.67L3.44 9.04l-.69-.29z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
