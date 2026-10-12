<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzi5_pbnu"/><path class="h8y00fb3y"/><rect class="h0oni2btl"/><path class="h185oac7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rickshaw-art" /></template>
<style>
.h0oni2btl {
  width: 17.5px;
  height: 2.5px;
  x: 3.25px;
  y: 16px;
  rx: 1px;
}

.h185oac7d {
  d: path("M5 18.5h3v1.75a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm11 0h3v1.75a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1Z");
}

.h8y00fb3y {
  d: path("M12 14c-2.5-1.75-3.5-3-3.5-4.25a1.75 1.75 0 0 1 3.5-.5a1.75 1.75 0 0 1 3.5.5c0 1.25-1 2.5-3.5 4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzi5_pbnu {
  d: path("M4.75 16v-6a7.25 7.25 0 0 1 14.5 0v6Z");
}

</style>
