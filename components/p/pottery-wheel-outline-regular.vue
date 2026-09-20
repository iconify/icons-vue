<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hya5w9myb"/><path class="ys-dg812g"/><path class="fmlaifbpn"/><path class="qdn88l2uv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pottery-wheel-outline-regular" /></template>
<style>
.fmlaifbpn {
  d: path("M12 16v4");
}

.hya5w9myb {
  d: path("M9 13c-2 -2 -1 -5 1 -7h4c2 2 3 5 1 7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qdn88l2uv {
  d: path("M7 20h10");
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
