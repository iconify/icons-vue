<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i4y-3bweq"/><path class="q0y85_d7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toilet-brush" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4y-3bweq {
  width: 6.5px;
  height: 6px;
  x: 3.25px;
  y: 2.75px;
  rx: 1.5px;
}

.q0y85_d7d {
  d: path("M2.75 11.25h18.5a7 7 0 0 1-6.5 7l.5 3h-6.5L9.5 18a7 7 0 0 1-6.75-6.75");
}

</style>
