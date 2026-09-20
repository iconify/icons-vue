<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w95bfobed"/><path class="uzf676bdq"/><path class="cw0e2h_ie"/><path class="lw1netb9x"/><path class="h-9ns0bya"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="x58_p1b1n"/><path class="aigfccrzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-load-duotone-thin" /></template>
<style>
.aigfccrzm {
  d: path("M19.5 8.5 22 11l-2.5 2.5");
}

.cw0e2h_ie {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h-9ns0bya {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.5 8.5 22 11l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldkstzszf {
  d: path("M3 16h11");
}

.lw1netb9x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrqy16b7j {
  d: path("M3 6h11");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.uzf676bdq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w95bfobed {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x58_p1b1n {
  d: path("M17 11h5");
}

</style>
