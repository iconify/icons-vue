<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ryvifbbnq"/><rect class="j757nou5k"/><path class="bgv6tbcmm"/><rect class="ogs0flb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:renovation" /></template>
<style>
.bgv6tbcmm {
  d: path("M17 6.75v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j757nou5k {
  width: 10px;
  height: 4px;
  x: 11.25px;
  y: 2.75px;
  rx: 1.5px;
}

.ogs0flb9y {
  width: 2.5px;
  height: 6.5px;
  x: 15.75px;
  y: 9.75px;
  rx: 1px;
}

.ryvifbbnq {
  d: path("M2.75 20.25V13.2q0-1 .78-1.62l3.69-2.96Q8 8 8.78 8.62l3.69 2.96q.78.62.78 1.62v7.05q0 1-1 1h-8.5q-1 0-1-1");
}

</style>
