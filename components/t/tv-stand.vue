<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="m_f-0fsug"/><path class="p3xp0rb2x"/><rect class="v-datx-di"/><path class="edis0bi-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tv-stand" /></template>
<style>
.edis0bi-s {
  d: path("M12 16.25v5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_f-0fsug {
  width: 15.5px;
  height: 10px;
  x: 4.25px;
  y: 2.75px;
  rx: 2px;
}

.p3xp0rb2x {
  d: path("M4.25 9.75h15.5m-7.75 3v3.5");
}

.v-datx-di {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 16.25px;
  rx: 1.5px;
}

</style>
