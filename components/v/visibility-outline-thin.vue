<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rp243mbkd"/><path class="bo51iypxr"/><path class="rkhcgsbdl"/><path class="irm-6r_xs"/><path class="uzi41e83o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:visibility-outline-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irm-6r_xs {
  d: path("M3 17v4");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.rp243mbkd {
  d: path("M6.36 9.95a6 6 0 0 1 11.28 0");
}

.uzi41e83o {
  d: path("M21 17v4");
}

</style>
