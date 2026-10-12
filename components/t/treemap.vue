<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kw2bt6bfe"/><rect class="ykbhgjpud"/><rect class="rmzrydbuk"/><rect class="iy5z0mbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:treemap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iy5z0mbdg {
  width: 6.5px;
  height: 2.5px;
  x: 14.75px;
  y: 18.75px;
  rx: 1px;
}

.kw2bt6bfe {
  width: 9.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.rmzrydbuk {
  width: 6.5px;
  height: 3.5px;
  x: 14.75px;
  y: 12.75px;
  rx: 1px;
}

.ykbhgjpud {
  width: 6.5px;
  height: 7.5px;
  x: 14.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
