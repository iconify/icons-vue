<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hx8itjbwv"/><path class="xycf6-bdn"/><path class="i-2dnzb7m"/><path class="qw7b_6b1t"/><path class="gfk1uw7pu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wine-tasting-duotone-regular" /></template>
<style>
.gfk1uw7pu {
  d: path("M9 8q3 3 6 0");
}

.hx8itjbwv {
  fill: currentColor;
  d: path("M7 4h10v4c0 4 -2 6 -5 6s-5 -2 -5 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i-2dnzb7m {
  d: path("M12 14v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.xycf6-bdn {
  d: path("M7 4h10v4c0 4 -2 6 -5 6s-5 -2 -5 -6Z");
}

</style>
