<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i9y1osboo"/><path class="l_0tu0bwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-in-down-right-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i9y1osboo {
  stroke-opacity: 0.4;
  d: path("M14 7L21 7L21 21L7 21L7 14");
}

.l_0tu0bwv {
  d: path("M2.7071 2.7071L10.8536 10.8536M2 11L11 11L11 2");
}

</style>
