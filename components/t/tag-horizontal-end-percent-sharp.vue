<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="evmv35z5s"/><path class="d9f73pbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-end-percent-sharp" /></template>
<style>
.d9f73pbit {
  fill: currentColor;
  d: path("M11.25 8.5C11.25 9.3284 11.9216 10 12.75 10C13.5784 10 14.25 9.3284 14.25 8.5C14.25 7.6716 13.5784 7 12.75 7C11.9216 7 11.25 7.6716 11.25 8.5ZM5.25 15.5C5.25 16.3284 5.9216 17 6.75 17C7.5784 17 8.25 16.3284 8.25 15.5C8.25 14.6716 7.5784 14 6.75 14C5.9216 14 5.25 14.6716 5.25 15.5Z");
  stroke: none;
}

.evmv35z5s {
  d: path("M2 4L14.8284 4L22 12L14.8284 20L2 20L2 4ZM13.0429 15.2929L6.4571 8.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
