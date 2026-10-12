<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vhmri5qmg"/><path class="kkjeo8bod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wardrobe" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkjeo8bod {
  d: path("M12 2.75V19.5m-2.5-10V12m5-2.5V12m-8.25 7.5v1.75m11.5-1.75v1.75");
}

.vhmri5qmg {
  width: 16.5px;
  height: 16.75px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
