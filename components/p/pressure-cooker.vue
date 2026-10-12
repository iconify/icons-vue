<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="m75vsidsx"/><path class="zdvqg1bhf"/><rect class="ivuuzbrqg"/><path class="qya1ambvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pressure-cooker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivuuzbrqg {
  width: 13.5px;
  height: 9.25px;
  x: 3px;
  y: 12px;
  rx: 2px;
}

.m75vsidsx {
  width: 2.5px;
  height: 3.5px;
  x: 8.5px;
  y: 2.75px;
  rx: 1px;
}

.qya1ambvp {
  d: path("M3 14.5h13.5");
}

.zdvqg1bhf {
  d: path("M3 9.5c0-2 3-3.25 6.75-3.25S16.5 7.5 16.5 9.5Zm13.5-1h4.75m-4.75 5h4.75");
}

</style>
