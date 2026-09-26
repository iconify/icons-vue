<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mmcw3q0_g"/><path class="vi-86ybww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:recycle-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mmcw3q0_g {
  stroke-opacity: 0.4;
  d: path("M7.1906 7.9945L9.7855 3.5C10.9402 1.5 13.827 1.5 14.9817 3.5L17.2879 7.4945M13.0674 6.3636L17.2879 7.4945L18.4187 3.274");
}

.vi-86ybww {
  d: path("M18.9992 10.4586L21.5941 14.953C22.7488 16.953 21.3054 19.453 18.996 19.453L14.3836 19.453M17.2235 16.6131L14.3836 19.453L17.2235 22.2929M11.3836 19.453L5.7712 19.453C3.4618 19.453 2.0184 16.953 3.1731 14.953L5.4793 10.9586M6.6102 15.179L5.4793 10.9586L1.2588 12.0894");
}

</style>
