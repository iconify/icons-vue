<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pb4-u9bmk"/><rect class="z8ltrbucw"/><path class="nk4z65bcc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pendant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk4z65bcc {
  d: path("M10 15.5a2 2.75 0 1 0 4 0a2 2.75 0 1 0-4 0");
}

.pb4-u9bmk {
  d: path("M6.5 2.75L12 8.5l5.5-5.75");
}

.z8ltrbucw {
  width: 9px;
  height: 11.5px;
  x: 7.5px;
  y: 9.75px;
  rx: 4.5px;
}

</style>
