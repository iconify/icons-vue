<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="povg_rnmz"/><path class="vy55o7bfi"/><path class="fwyf93qcw"/><path class="eur7p0b8m"/><path class="bu057zbzx"/><path class="eoov2wehu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stand-reminder-duotone-thin" /></template>
<style>
.bu057zbzx {
  d: path("M17 19V9");
}

.eoov2wehu {
  d: path("m14 12 3 -3 3 3");
}

.eur7p0b8m {
  d: path("m4 18 4 -4 4 4");
}

.fwyf93qcw {
  d: path("M8 8v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.povg_rnmz {
  fill: currentColor;
  d: path("M5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vy55o7bfi {
  d: path("M5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
