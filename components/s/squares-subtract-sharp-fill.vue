<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="g8zu1lkdq"/><path class="n-58p46of"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:squares-subtract-sharp-fill" /></template>
<style>
.g8zu1lkdq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2L15 2C15.5523 2 16 2.4477 16 3L16 9C16 9.5523 15.5523 10 15 10L10 10L10 15C10 15.5523 9.5523 16 9 16L3 16C2.4477 16 2 15.5523 2 15L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n-58p46of {
  d: path("M18 9L21 9L21 13.5M21 16.5L21 21L16.5 21M13.5 21L9 21L9 18");
}

</style>
