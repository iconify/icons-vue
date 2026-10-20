<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uro6d3bfc"/><path class="a_enazu7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:symmetry-horizontal-sharp-two-tone" /></template>
<style>
.a_enazu7x {
  d: path("M7 5L17 5L22 19L2 19ZM12 1L12 23");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uro6d3bfc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 4L17 4C17.4226 4 17.7996 4.2657 17.9417 4.6637L22.9417 18.6637C22.9803 18.7716 23 18.8854 23 19C23 19.5523 22.5523 20 22 20L2 20C1.4477 20 1 19.5523 1 19C1 18.8854 1.0197 18.7716 1.0583 18.6637L6.0583 4.6637C6.2004 4.2657 6.5774 4 7 4Z");
  stroke: none;
}

</style>
