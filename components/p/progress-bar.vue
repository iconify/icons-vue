<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kgrlkn5lt"/><path class="d_8znhbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:progress-bar" /></template>
<style>
.d_8znhbno {
  d: path("M6.25 12h7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgrlkn5lt {
  width: 18.5px;
  height: 7px;
  x: 2.75px;
  y: 8.5px;
  rx: 3.5px;
}

</style>
