<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rgf1jio2v"/><path class="wz5ie-ptf"/><rect class="ay6j63oco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:midi-keyboard" /></template>
<style>
.ay6j63oco {
  width: 3.75px;
  height: 3.5px;
  x: 17.5px;
  y: 3.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rgf1jio2v {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 11.25px;
  rx: 2px;
}

.wz5ie-ptf {
  d: path("M7.4 14.75v6.5m4.6-6.5v6.5m4.6-6.5v6.5m-4.6-10V8.5c0-2 1.5-3.5 3.5-3.5h2");
}

</style>
