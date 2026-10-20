<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="upc_w_i0j"/><path class="l_-q8pbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pyramid-two-tone" /></template>
<style>
.l_-q8pbht {
  d: path("M2.1809 16.032L12 2L21.8191 16.032C22.1736 16.5385 21.988 17.2422 21.4298 17.5081L12 22L2.5702 17.5081C2.012 17.2422 1.8264 16.5385 2.1809 16.032ZM12 2L12 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.upc_w_i0j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.1402 18.4109C1.4438 18.0792 1.0002 17.3766 1.0002 16.6053C1.0002 16.195 1.1264 15.7947 1.3616 15.4586L11.1807 1.4267C11.3678 1.1593 11.6736 1 12 1C12.3264 1 12.6322 1.1593 12.8193 1.4267L22.6384 15.4586C22.8736 15.7947 22.9998 16.195 22.9998 16.6053C22.9998 17.3766 22.5562 18.0792 21.8598 18.4109L12.4301 22.9028C12.2957 22.9668 12.1488 23 12 23C11.8512 23 11.7043 22.9668 11.5699 22.9028L2.1402 18.4109Z");
  stroke: none;
}

</style>
