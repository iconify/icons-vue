<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bkvs37v4d"/><rect class="tjczw_npf"/><rect class="zmyq7-bqa"/><path class="g3bxqq7ow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radiator" /></template>
<style>
.bkvs37v4d {
  width: 3px;
  height: 15.75px;
  x: 3.75px;
  y: 3.75px;
  rx: 1.5px;
}

.g3bxqq7ow {
  d: path("M6.75 7h2.5m3 0h2.5m-8 9h2.5m3 0h2.5m3 0h2.5m0-1.75v3.5m-15 1.75v1.75m11-1.75v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tjczw_npf {
  width: 3px;
  height: 15.75px;
  x: 9.25px;
  y: 3.75px;
  rx: 1.5px;
}

.zmyq7-bqa {
  width: 3px;
  height: 15.75px;
  x: 14.75px;
  y: 3.75px;
  rx: 1.5px;
}

</style>
