<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hp089_qyc"/><path class="vgcupwbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunset-2-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hp089_qyc {
  stroke-opacity: 0.4;
  d: path("M1.7241 14.7897L2 14.5C2.9123 13.5421 4.1772 13 5.5 13C6.8228 13 8.0877 13.5421 9 14.5C9.9123 15.4579 11.1772 16 12.5 16C13.8228 16 15.0877 15.4579 16 14.5C16.9123 13.5421 18.1772 13 19.5 13C20.4 13 21.3 13.25 22 13.7L22.4592 13.9952M1.7241 19.7897L2 19.5C2.9123 18.5421 4.1772 18 5.5 18C6.8228 18 8.0877 18.5421 9 19.5C9.9123 20.4579 11.1772 21 12.5 21C13.8228 21 15.0877 20.4579 16 19.5C16.9123 18.5421 18.1772 18 19.5 18C20.4 18 21.3 18.25 22 18.7L22.4592 18.9952");
}

.vgcupwbcw {
  d: path("M4.0801 9.8707C4.6425 5.9267 8.0212 2.9974 12.0051 3C15.9891 3.0026 19.364 5.9361 19.9213 9.8809");
}

</style>
