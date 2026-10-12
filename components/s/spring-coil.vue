<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="db0mml2kj"/><rect class="koz6vwrva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spring-coil" /></template>
<style>
.db0mml2kj {
  d: path("M6.5 2.75h11m-5.5 0V5c5.5 0 5.5 2.5 0 2.5S6.5 10 12 10s5.5 2.5 0 2.5S6.5 15 12 15v1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.koz6vwrva {
  width: 8.5px;
  height: 4.75px;
  x: 7.75px;
  y: 16.5px;
  rx: 1.5px;
}

</style>
