<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o5vaeiwtr"/><path class="ucxk7b0pm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ungroup-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5vaeiwtr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.5 2L21 2C21.5523 2 22 2.4477 22 3L22 12C22 12.5523 21.5523 13 21 13L12 13C11.4477 13 11 12.5523 11 12L11 3C11 2.4477 11.4477 2 12 2Z");
  stroke: none;
}

.ucxk7b0pm {
  d: path("M9 12L3 12L3 21L12 21L12 15M8 2L8 5.5M2 8L5.5 8M16 18.5L16 22M18.5 16L22 16");
}

</style>
