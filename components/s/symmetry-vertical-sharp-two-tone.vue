<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k5kflbc1c"/><path class="g7zr2d2ux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:symmetry-vertical-sharp-two-tone" /></template>
<style>
.g7zr2d2ux {
  d: path("M5 17L5 7L19 2L19 22ZM1 12L23 12");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k5kflbc1c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 17L4 7C4 6.5774 4.2657 6.2004 4.6637 6.0583L18.6637 1.0583C18.7716 1.0197 18.8854 1 19 1C19.5523 1 20 1.4477 20 2L20 22C20 22.5523 19.5523 23 19 23C18.8854 23 18.7716 22.9803 18.6637 22.9417L4.6637 17.9417C4.2657 17.7996 4 17.4226 4 17Z");
  stroke: none;
}

</style>
