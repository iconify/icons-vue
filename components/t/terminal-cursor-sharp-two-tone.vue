<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v76bgnbew"/><path class="ccwslmg7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-cursor-sharp-two-tone" /></template>
<style>
.ccwslmg7r {
  d: path("M21 18.9999L12 18.9999M15 4.6997L11.1917 16.2002L8.5317 10.5103L3.9995 8.208L15 4.6997Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v76bgnbew {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.5789 14.9797L14.7027 5.3519C14.8263 4.9622 14.4555 4.5969 14.0677 4.7264L4.3411 7.7852C3.9028 7.9316 3.8807 8.5435 4.3074 8.7211L8.353 10.4361C8.468 10.484 8.561 10.5731 8.6138 10.6859L10.6494 15.0402C10.8422 15.4527 11.4412 15.4137 11.5789 14.9797Z");
  stroke: none;
}

</style>
