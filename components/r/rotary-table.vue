<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gge08bbsr"/><path class="iren7cb1n"/><path class="uhfchpnpb"/><path class="m2wceccgo"/><path class="aslbbf-5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rotary-table" /></template>
<style>
.aslbbf-5x {
  d: path("M15.75 4.75h2.75V2");
}

.gge08bbsr {
  d: path("M2.5 12.5a9.5 4.5 0 1 0 19 0a9.5 4.5 0 1 0-19 0Z");
}

.iren7cb1n {
  d: path("M2.5 12.5V16a9.5 4.5 0 0 0 19 0v-3.5");
}

.m2wceccgo {
  d: path("M3.5 7a10 9.5 0 0 1 15-2.25");
}

.uhfchpnpb {
  fill: currentColor;
  d: path("m12 10.75l3 1.75l-3 1.75l-3-1.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
