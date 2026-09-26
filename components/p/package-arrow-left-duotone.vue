<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f1wb2ccqt"/><path class="p4a0wlb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-left-duotone" /></template>
<style>
.f1wb2ccqt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.3613 1.3266L21.3613 5.4003C22.3668 5.9123 23 6.9453 23 8.0737L23 12C23 12.5523 22.5523 13 22 13L16 13C14.3431 13 13 14.3431 13 16L13 22C13 22.5523 12.5523 23 12 23C11.5332 23 11.0663 22.8911 10.6387 22.6734L2.6387 18.5997C1.6332 18.0877 1 17.0547 1 15.9263L1 8.0737C1 6.9453 1.6332 5.9123 2.6387 5.4003L10.6387 1.3266C11.494 0.8911 12.506 0.8911 13.3613 1.3266Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4a0wlb-s {
  d: path("M2.3084 7.0066L12 12M12 12L21.6916 7.0066M7 4.3017L17 9.4239M12 12L12 22M22 19L16 19M19 16L16 19L19 22");
}

</style>
