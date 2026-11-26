<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mg8kbeyiu"/><path class="gzo17ybhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skirt-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gzo17ybhn {
  d: path("M18 8L18 4L6 4L6 8M15.6667 20L14 8M8.3333 20L10 8M6 8L2.0025 20L8.3333 20L15.6667 20L21.9975 20L18 8M6 8L10 8L14 8L18 8");
}

.mg8kbeyiu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7.838L5 4C5 3.4477 5.4477 3 6 3L12 3L18 3C18.5523 3 19 3.4477 19 4L19 7.838L22.9462 19.684C22.9802 19.7859 22.9975 19.8926 22.9975 20C22.9975 20.5523 22.5498 21 21.9975 21L12 21L2.0025 21C1.4502 21 1.0025 20.5523 1.0025 20C1.0025 19.8926 1.0198 19.7859 1.0538 19.684Z");
  stroke: none;
}

</style>
