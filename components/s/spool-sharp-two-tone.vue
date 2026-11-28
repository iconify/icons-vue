<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lzeh0z7yg"/><path class="r8gvtpb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spool-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lzeh0z7yg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7L4 7C3.4477 7 3 6.5523 3 6L3 2C3 1.4477 3.4477 1 4 1L12 1L20 1C20.5523 1 21 1.4477 21 2L21 6C21 6.5523 20.5523 7 20 7L18 7L18 17L20 17C20.5523 17 21 17.4477 21 18L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 18C3 17.4477 3.4477 17 4 17L6 17Z");
  stroke: none;
}

.r8gvtpb4m {
  d: path("M4 2L20 2L20 6L4 6ZM4 18L20 18L20 22L4 22ZM7 6L7 18M17 6L17 18M7 13.5L17 10.5");
}

</style>
