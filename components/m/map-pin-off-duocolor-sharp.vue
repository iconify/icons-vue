<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lmxlbqbeq"/><path class="gy598ib9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-off-duocolor-sharp" /></template>
<style>
.gy598ib9y {
  d: path("M17.036 16.036C15.612 18.186 13.654 19.897 12 21c-3-2-7-6-7-11c0-1.678.59-3.219 1.575-4.425m3.652-2.348A7 7 0 0 1 19 10c0 .624-.062 1.232-.177 1.823");
}

.lmxlbqbeq {
  stroke-opacity: 0.4;
  d: path("m3 2l19 19");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
