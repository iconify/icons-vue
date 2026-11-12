<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kruqtab-m"/><path class="i8utatbio"/><path class="vepd3ytoq"/><path class="un-u7xpwr"/><path class="qpmqs1x2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scanner-2-line-duotone" /></template>
<style>
.i8utatbio {
  d: path("M22 14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kruqtab-m {
  d: path("M6 13C6 13 7.8 11 12 11C16.2 11 18 13 18 13");
}

.qpmqs1x2s {
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.un-u7xpwr {
  d: path("M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vepd3ytoq {
  d: path("M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
