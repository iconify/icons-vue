<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y48yejbzu"/><path class="dylew4bbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-bag-check-sharp-two-tone" /></template>
<style>
.dylew4bbx {
  d: path("M15 10L15 11C15 12.6569 13.6569 14 12 14C10.3431 14 9 12.6569 9 11L9 10M13.7071 18.7071L16 21L20.2929 16.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y48yejbzu {
  stroke-opacity: 0.4;
  d: path("M4.0572 7L19.9428 7M11 21L4 21L4 7L7 3L16.9999 3L20 7L20 13");
}

</style>
