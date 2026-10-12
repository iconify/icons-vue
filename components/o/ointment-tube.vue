<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oj9isbwwy"/><path class="de5nlr-bz"/><rect class="fj86j38ll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ointment-tube" /></template>
<style>
.de5nlr-bz {
  d: path("M6.25 7.75h7.25q1 0 1.74.67l1.02.91Q17 10 17 11v2q0 1-.74 1.67l-1.02.91q-.74.67-1.74.67H6.25q-1 0-1-1v-6.5q0-1 1-1M8 12h4.5");
}

.fj86j38ll {
  width: 4.25px;
  height: 3.5px;
  x: 17px;
  y: 10.25px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oj9isbwwy {
  width: 2.5px;
  height: 10px;
  x: 2.75px;
  y: 7px;
  rx: 0.75px;
}

</style>
