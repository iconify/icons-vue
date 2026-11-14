<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f7ylvacjb"/><path class="btz3-54sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mansion" /></template>
<style>
.btz3-54sg {
  d: path("M10.5 21.5v-3.75a1.5 1.5 0 0 1 3 0v3.75m-1.5-11h.01M5.5 16h.01m12.99 0h.01");
}

.f7ylvacjb {
  d: path("M2.5 21.5v-10h6v-4l3.5-4l3.5 4v4h6v10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
