<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h_v9ydx1e"/><rect class="vuqezq39b"/><rect class="vjq2goblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pipe-flange" /></template>
<style>
.h_v9ydx1e {
  d: path("M5.75 5.25H15A4.75 4.75 0 0 1 19.75 10v8h-5v-7.75h-9Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjq2goblm {
  width: 7.5px;
  height: 3px;
  x: 13.5px;
  y: 18px;
  rx: 1px;
}

.vuqezq39b {
  width: 3px;
  height: 8px;
  x: 2.75px;
  y: 3.75px;
  rx: 1px;
}

</style>
