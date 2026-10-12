<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hnh21gnmq"/><path class="jfe_ovbfd"/><path class="ix10u2bde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:memory-card-camera-sharp" /></template>
<style>
.hnh21gnmq {
  d: path("M4.75 4.75H17.5l1.41 1.41l.93.93l1.41 1.41v10.75H2.75V4.75zm1.25 0v3m3-3v3m3-3v3");
}

.ix10u2bde {
  d: path("M13.25 14a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 1 1 2.5 0");
}

.jfe_ovbfd {
  d: path("M7.75 11.25h8.5v5.5h-8.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
