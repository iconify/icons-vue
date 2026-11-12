<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sgr_f8btx"/><path class="mzgayy21e"/><path class="p8mxsubsi"/><path class="xa3dxb-md"/><path class="p2fvfob4y"/><path class="h0mdmlb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:projector-linear" /></template>
<style>
.h0mdmlb_j {
  stroke-linejoin: round;
  d: path("M5.5 9.5L5.5002 11.0001");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzgayy21e {
  d: path("M6 18L5 20");
}

.p2fvfob4y {
  stroke-linejoin: round;
  d: path("M12 9C12 10.1046 12.8954 11 14 11C15.1046 11 16 10.1046 16 9C16 7.89543 15.1046 7 14 7");
}

.p8mxsubsi {
  stroke-linejoin: round;
  d: path("M10 6H8C5.17157 6 3.75736 6 2.87868 6.87868C2 7.75736 2 9.17157 2 12C2 14.8284 2 16.2426 2.87868 17.1213C3.75736 18 5.17157 18 8 18H16C18.8284 18 20.2426 18 21.1213 17.1213C22 16.2426 22 14.8284 22 12C22 9.17157 22 7.75736 21.1213 6.87868C20.4819 6.23925 19.5589 6.06515 18.0136 6.01774");
}

.sgr_f8btx {
  d: path("M18 18L19 20");
}

.xa3dxb-md {
  stroke-linejoin: round;
  d: path("M19 9C19 11.7614 16.7614 14 14 14C11.2386 14 9 11.7614 9 9C9 7.87439 9.37194 6.83566 9.99963 6C10.9118 4.78555 12.3642 4 14 4C15.6438 4 17.1023 4.79321 18.0136 6.01774C18.6333 6.85034 19 7.88234 19 9Z");
}

</style>
