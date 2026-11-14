<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrlqveelm"/><path class="bq42kvbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:presentation-cast" /></template>
<style>
.bq42kvbax {
  d: path("M13.5 2.25a8.25 8.25 0 0 1 8.25 8.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrlqveelm {
  d: path("M2.5 10.5h11v8h-11Zm5.5 8v3m-3 0h6m2.5-13.75a2.75 2.75 0 0 1 2.75 2.75M13.5 5a5.5 5.5 0 0 1 5.5 5.5");
}

</style>
