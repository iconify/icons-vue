<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b5j-xvxce"/><path class="u_9vgsopu"/><circle class="qwbipkbye"/><path class="gpxfncb1k"/><path class="h0mdmlb_j"/><path class="vmte-ktqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:projector-line-duotone" /></template>
<style>
.b5j-xvxce {
  d: path("M18 18L19 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gpxfncb1k {
  d: path("M12 9C12 10.1046 12.8954 11 14 11C15.1046 11 16 10.1046 16 9C16 7.89543 15.1046 7 14 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

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

.qwbipkbye {
  cx: 14px;
  cy: 9px;
  r: 5px;
}

.u_9vgsopu {
  d: path("M6 18L5 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vmte-ktqc {
  d: path("M10 6H8C5.17157 6 3.75736 6 2.87868 6.87868C2 7.75736 2 9.17157 2 12C2 14.8284 2 16.2426 2.87868 17.1213C3.75736 18 5.17157 18 8 18H16C18.8284 18 20.2426 18 21.1213 17.1213C22 16.2426 22 14.8284 22 12C22 9.17157 22 7.75736 21.1213 6.87868C20.4819 6.23925 19.5589 6.06515 18.0136 6.01774");
}

</style>
