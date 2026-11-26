<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q8_aoq06v"/><path class="l2fd4qopw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:snorkel-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l2fd4qopw {
  d: path("M22 4L22 19L10 19L9 19");
}

.q8_aoq06v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 7L18 7C18.5523 7 19 7.4477 19 8L19 15C19 15.5523 18.5523 16 18 16L12.5 16C12.2348 16 11.9804 15.8946 11.7929 15.7071L10 13.9L8.2071 15.7071C8.0196 15.8946 7.7652 16 7.5 16L2 16C1.4477 16 1 15.5523 1 15L1 8C1 7.4477 1.4477 7 2 7Z");
  stroke: none;
}

</style>
