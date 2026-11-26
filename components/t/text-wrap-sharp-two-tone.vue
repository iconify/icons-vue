<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uu918dbyn"/><path class="zjpnhcbhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-wrap-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uu918dbyn {
  stroke-opacity: 0.4;
  d: path("M2 3L22 3M2 15L3 15L8 15L9 15M2 21L15 21L16 21");
}

.zjpnhcbhd {
  d: path("M2 9L3 9L18 9C19.6569 9 21 10.3431 21 12C21 13.6569 19.6569 15 18 15L12 15M14.2929 12.7071L14 13L12 15L14 17L14.2929 17.2929");
}

</style>
