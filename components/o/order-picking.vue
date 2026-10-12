<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="icydrxplj"/><path class="q-6prybqy"/><rect class="mr0ir1bhl"/><path class="ze7l-fbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:order-picking" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icydrxplj {
  width: 10.5px;
  height: 15.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.mr0ir1bhl {
  width: 5.75px;
  height: 8.75px;
  x: 15.5px;
  y: 12.5px;
  rx: 1.25px;
}

.q-6prybqy {
  d: path("M5.75 6.75h5m-5 3.25h5m-5 3.25h2.5");
}

.ze7l-fbjh {
  d: path("M18.38 12.5v3");
}

</style>
