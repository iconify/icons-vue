<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="emg-pk9hg"/><path class="qlvg9o9nq"/><path class="w1z2onnqz"/><path class="q6y5l5b-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-3d-line-duotone" /></template>
<style>
.emg-pk9hg {
  stroke-linejoin: round;
  d: path("M13.0137 7.3381L9.83791 4.16235L6.66221 7.33801");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6y5l5b-j {
  d: path("M9.83782 4.16235L9.83761 14.1621M9.83761 14.1621L19.8377 14.1622M9.83761 14.1621L4.16266 19.8379");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qlvg9o9nq {
  stroke-linejoin: round;
  d: path("M4.16234 15.3467L4.1624 19.8379L8.65348 19.838");
}

.w1z2onnqz {
  stroke-linejoin: round;
  d: path("M16.6622 17.3376L19.8378 14.1621L16.6622 10.9868");
}

</style>
