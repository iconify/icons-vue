<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ehvte120k"/><path class="w2x086bvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-sharp-fill" /></template>
<style>
.ehvte120k {
  fill: currentColor;
  d: path("M4 17.25L4 13.75L9 13.75L9 10.25L14 10.25L14 6.75L20 6.75L20 17.25L4 17.25Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w2x086bvu {
  stroke-linejoin: miter;
  d: path("M1 17.25L23 17.25M4 17.25L4 13.75L9 13.75L9 10.25L14 10.25L14 6.75L20 6.75L20 17.25L4 17.25Z");
}

</style>
