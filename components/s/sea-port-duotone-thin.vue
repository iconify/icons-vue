<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="brrdcmt-d"/><path class="yo2xhpbcn"/><path class="rdjfllbip"/><path class="k85h_vh6j"/><path class="axz8bmb1c"/><path class="h69dzcbeh"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sea-port-duotone-thin" /></template>
<style>
.axz8bmb1c {
  d: path("M17 4v6");
}

.brrdcmt-d {
  fill: currentColor;
  d: path("M14 10h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h69dzcbeh {
  d: path("M14 10h6v4h-6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k85h_vh6j {
  d: path("m5 9 5 -5");
}

.rdjfllbip {
  d: path("M5 4h14");
}

.yo2xhpbcn {
  d: path("M5 4v15");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
