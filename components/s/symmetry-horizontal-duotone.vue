<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l_uo7pbfz"/><path class="x1f4lc3zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:symmetry-horizontal-duotone" /></template>
<style>
.l_uo7pbfz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.6832 4L16.3168 4C17.1408 4 17.8805 4.5054 18.18 5.273L22.8623 17.2731C22.9527 17.5047 22.9991 17.7513 22.9991 18C22.9991 19.1045 22.1037 20 20.9991 20L3.0009 20C1.8964 20 1.001 19.1046 1.001 18.0001C1.001 17.7513 1.0474 17.5047 1.1378 17.273L5.82 5.2729C6.1196 4.5053 6.8592 4 7.6832 4Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x1f4lc3zb {
  d: path("M12 2L12 22");
}

</style>
