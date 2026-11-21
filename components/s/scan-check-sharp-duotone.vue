<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i_2jq7bdt"/><path class="fgbmi7b1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-check-sharp-duotone" /></template>
<style>
.fgbmi7b1u {
  d: path("M7.7071 11.2071L8 11.5L11 14.5L16 9.5L16.2929 9.2071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i_2jq7bdt {
  stroke-opacity: 0.4;
  d: path("M3 9L3 8L3 3L8 3L9 3M15 3L16 3L21 3L21 8L21 9M21 15L21 16L21 21L16 21L15 21M9 21L8 21L3 21L3 16L3 15");
}

</style>
