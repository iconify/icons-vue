<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="edcmcbcrd"/><path class="d22-dr87j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:treasure-sharp-two-tone" /></template>
<style>
.d22-dr87j {
  d: path("M2 11L6 11L10 11M6 4.1L6 11L6 20M18 4.1L18 11L18 20M22 11L18 11L14 11M14 11L14 9L10 9L10 11L10 13C10 14.1046 10.8954 15 12 15C13.1046 15 14 14.1046 14 13ZM18 4.1C17.6769 4.0344 17.3425 4 17 4L7 4C6.6575 4 6.3231 4.0344 6 4.1C3.7178 4.5633 2 6.5811 2 9L2 11L2 20L6 20L18 20L22 20L22 11L22 9C22 6.5811 20.2822 4.5633 18 4.1Z");
}

.edcmcbcrd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21L6 21L2 21C1.4477 21 1 20.5523 1 20L1 11L1 9C1 6.0961 3.062 3.676 5.801 3.12C6.1893 3.0412 6.5904 3 7 3L17 3C17.4096 3 17.8107 3.0412 18.1989 3.12C20.938 3.676 23 6.0961 23 9L23 11L23 20C23 20.5523 22.5523 21 22 21L18 21Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
