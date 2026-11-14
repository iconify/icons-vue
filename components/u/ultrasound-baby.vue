<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qrqib4b2h"/><path class="fswyq4b2c"/><path class="og2jpybff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ultrasound-baby" /></template>
<style>
.fswyq4b2c {
  d: path("M10.5 12.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og2jpybff {
  d: path("M10.75 13.75C9.25 14.75 9 17 10.5 18c1.25.75 3.25.5 4.25-.75");
}

.qrqib4b2h {
  d: path("M12 2.5L3 17c3 3 6 4.25 9 4.25S18 20 21 17Z");
}

</style>
