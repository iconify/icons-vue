<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p99nrmbpu"/><path class="ae2dzwofq"/><path class="cyibsnbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:print-run" /></template>
<style>
.ae2dzwofq {
  d: path("M8 9V6h9v6");
}

.cyibsnbck {
  d: path("M11 6V3h8v9m-9.5 4.5h5");
}

.p99nrmbpu {
  d: path("M3 12h18l-1.5 9h-15Zm2 0V9h9v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
