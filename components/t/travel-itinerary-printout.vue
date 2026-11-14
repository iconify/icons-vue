<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcwosebch"/><path class="p1tpbpb4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:travel-itinerary-printout" /></template>
<style>
.hcwosebch {
  d: path("M4 9h16v8H4Zm3.5 0V3.5h9V9");
}

.p1tpbpb4s {
  d: path("M7.5 14h9v6.5h-9Zm2.5 3h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
