<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="akmzub58u"/><path class="tqr92nbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:red-eye" /></template>
<style>
.akmzub58u {
  d: path("M2.5 11.5c2.5-4 6-6 9.5-6s7 2 9.5 6c-2.5 4-6 6-9.5 6s-7-2-9.5-6Z");
}

.tqr92nbmc {
  d: path("M9 11.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 0h.01m-7.26 0L6.5 11l.75 1m12-.5L17.5 11l-.75-1M18 13.75l-1.5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
