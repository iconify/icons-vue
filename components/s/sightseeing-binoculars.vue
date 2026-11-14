<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nckfslbcj"/><path class="i-ew4jjjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sightseeing-binoculars" /></template>
<style>
.i-ew4jjjn {
  d: path("M7 10.5L8.5 5H10m7 5.5L15.5 5H14m-4 0h4");
}

.nckfslbcj {
  d: path("M3 14.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm10 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
