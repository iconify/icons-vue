<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la5qfrrxr"/><rect class="lcoz0hb_e"/><path class="p5b263b2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vaccine-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la5qfrrxr {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2.5px;
}

.lcoz0hb_e {
  width: 6.25px;
  height: 2.5px;
  x: 6.75px;
  y: 8.25px;
  rx: 0.75px;
}

.p5b263b2j {
  d: path("M13 9.5h3m-10.75 0h1.5m-1 4.5h12.5m-12.5 2.25h8");
}

</style>
