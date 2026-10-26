<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="dv8_hrg5v"/><path class="mzh6dybyq"/><path class="jguyt6bee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-front-off-two-tone" /></template>
<style>
.dv8_hrg5v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M21 6L21 15C21.0006 15.5054 20.9052 16.0064 20.7188 16.4762L5.5238 1.2812C5.9936 1.0948 6.4946 0.9994 7 1L17 1C18.8242 1.0002 20.4173 2.2339 20.874 4L22 4C22.5523 4 23 4.4477 23 5C23 5.5523 22.5523 6 22 6L21 6ZM16.1715 19L7 19C4.7909 19 3 17.2091 3 15L3 5C2.9992 4.4323 3.1197 3.8709 3.3535 3.3535L18.6465 18.6466C18.1291 18.8803 17.5677 19.0008 17 19.0001L16.1715 19Z");
  stroke: none;
}

.jguyt6bee {
  fill: currentColor;
  d: path("M10 13.5C10 14.3284 9.3284 15 8.5 15C7.6716 15 7 14.3284 7 13.5C7 12.6716 7.6716 12 8.5 12C9.3284 12 10 12.6716 10 13.5Z");
  stroke: none;
}

.mzh6dybyq {
  d: path("M17.8715 17.8715C17.5957 17.9551 17.3031 18 17 18L7 18C5.3431 18 4 16.6569 4 15L4 5C4 4.6969 4.0449 4.4043 4.1285 4.1285M4 9L9 9M4 5L2 5M7 18L5 22M17 18L19 22M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
