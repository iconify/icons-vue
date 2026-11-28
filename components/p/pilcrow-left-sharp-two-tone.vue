<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="thr-43drr"/><path class="adxj6-b1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pilcrow-left-sharp-two-tone" /></template>
<style>
.adxj6-b1q {
  d: path("M22 17L3 17M7.2929 12.7071L3 17L7.2929 21.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.thr-43drr {
  stroke-opacity: 0.4;
  d: path("M22 3L13 3C11.3431 3 10 4.3431 10 6C10 7.6569 11.3431 9 13 9L15 9M15 3L15 14M20 3L20 14");
}

</style>
