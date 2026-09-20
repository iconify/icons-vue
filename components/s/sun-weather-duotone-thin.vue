<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfzmy-bgb"/><path class="gcurcebny"/><path class="faqh69b5q"/><path class="qc36m6bjs"/><path class="i2wbmzb2w"/><path class="o37zm_b2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sun-weather-duotone-thin" /></template>
<style>
.faqh69b5q {
  d: path("M3.5 3.5 6 6");
}

.gcurcebny {
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.gfzmy-bgb {
  fill: currentColor;
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2wbmzb2w {
  d: path("M3.5 20.5 6 18");
}

.o37zm_b2b {
  d: path("M20.5 20.5 18 18");
}

.qc36m6bjs {
  d: path("M20.5 3.5 18 6");
}

</style>
