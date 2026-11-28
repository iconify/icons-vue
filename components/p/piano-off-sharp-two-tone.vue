<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ekj58qb7z"/><path class="dafwtm6an"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piano-off-sharp-two-tone" /></template>
<style>
.dafwtm6an {
  d: path("M20 20L2 20L2 4L4 4M6 6L6 13L10 13L10 10M8 13L8 20M1.7071 1.7071L22.2929 22.2929");
}

.ekj58qb7z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3L3 3ZM6.7426 3L12 3L22 3C22.5523 3 23 3.4477 23 4L23 19.2574Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
