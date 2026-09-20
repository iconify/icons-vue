<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yo2xhpbcn"/><path class="rdjfllbip"/><path class="k85h_vh6j"/><path class="axz8bmb1c"/><path class="h69dzcbeh"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sea-port-outline-bold" /></template>
<style>
.axz8bmb1c {
  d: path("M17 4v6");
}

.h69dzcbeh {
  d: path("M14 10h6v4h-6Z");
}

.k85h_vh6j {
  d: path("m5 9 5 -5");
}

.rdjfllbip {
  d: path("M5 4h14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yo2xhpbcn {
  d: path("M5 4v15");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
