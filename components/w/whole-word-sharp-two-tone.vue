<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="m1dmxobcp"/><path class="e2wn6cbko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:whole-word-sharp-two-tone" /></template>
<style>
.e2wn6cbko {
  d: path("M10 11C10 12.6569 8.6569 14 7 14C5.3431 14 4 12.6569 4 11C4 9.3431 5.3431 8 7 8C8.6569 8 10 9.3431 10 11ZM10 7L10 15M14 3L14 15M20 11C20 12.6569 18.6569 14 17 14C15.3431 14 14 12.6569 14 11C14 9.3431 15.3431 8 17 8C18.6569 8 20 9.3431 20 11Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.m1dmxobcp {
  stroke-opacity: 0.4;
  d: path("M2 16L2 20L22 20L22 16");
}

</style>
