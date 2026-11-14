<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m5yvd7zgb"/><path class="mcmi4cctf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:zombie-computer" /></template>
<style>
.m5yvd7zgb {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8M7.75 6.75l2.5 2.5m0-2.5l-2.5 2.5m6-2.5l2.5 2.5m0-2.5l-2.5 2.5");
}

.mcmi4cctf {
  d: path("m9 13l1.5-1.25L12 13l1.5-1.25L15 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
