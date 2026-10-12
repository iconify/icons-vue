<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="bt252gbqe"/><path class="k82t55f8z"/><path class="cmwg7mb-v"/><path class="q14onebvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:public-transit-eco" /></template>
<style>
.bt252gbqe {
  width: 14.5px;
  height: 15.5px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.cmwg7mb-v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 15h.01M16 15h.01");
}

.k82t55f8z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12h14.5M9.5 10c.25-3 1.75-4.5 5-5c-.25 3-1.75 4.5-5 5");
}

.q14onebvy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 18.25v3m9.5-3v3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
