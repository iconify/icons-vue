<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><path class="kcf52vx4u"/><circle class="rh1oi0w6a"/><path class="knq-qlk1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:multimeter" /></template>
<style>
.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kcf52vx4u {
  d: path("M7.75 5.75h8.5V9.5h-8.5Z");
}

.knq-qlk1t {
  d: path("m12 15.25l1.5-1.5");
}

.rh1oi0w6a {
  cx: 12px;
  cy: 15.25px;
  r: 3.25px;
}

</style>
