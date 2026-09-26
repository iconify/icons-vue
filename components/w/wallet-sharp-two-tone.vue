<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v0vut1rsh"/><path class="bual0lami"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-sharp-two-tone" /></template>
<style>
.bual0lami {
  d: path("M5 3L18 3L18 7L21 7L21 21L3 21L3 5C3 3.8954 3.8954 3 5 3ZM3 5C3 6.1046 3.8954 7 5 7L18 7M21 12L16 12L16 16L21 16");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v0vut1rsh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2L18 2C18.5523 2 19 2.4477 19 3L19 6L21 6C21.5523 6 22 6.4477 22 7L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 5C2 3.3431 3.3431 2 5 2Z");
  stroke: none;
}

</style>
