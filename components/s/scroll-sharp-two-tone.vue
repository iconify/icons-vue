<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="drhhzbtfx"/><path class="k9lri1-6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scroll-sharp-two-tone" /></template>
<style>
.drhhzbtfx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22L7 22C6.4477 22 6 21.5523 6 21L6 10L2 10C1.4477 10 1 9.5523 1 9L1 6L1 3C1 2.4477 1.4477 2 2 2L7 2L18 2C18.5523 2 19 2.4477 19 3L19 9.5L19 15L22 15C22.5523 15 23 15.4477 23 16L23 21C23 21.5523 22.5523 22 22 22L17 22Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k9lri1-6b {
  d: path("M18 16L18 3L2 3L2 9L7 9M7 3L7 21L22 21L22 16L12 16L12 21M10 8L15 8M10 12L15 12");
}

</style>
