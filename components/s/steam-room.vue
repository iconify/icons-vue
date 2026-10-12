<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cnkmunb4t"/><rect class="ch6w80erw"/><path class="c9xi4lf6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steam-room" /></template>
<style>
.c9xi4lf6k {
  d: path("M5.5 17v4.25m13-4.25v4.25");
}

.ch6w80erw {
  width: 18.5px;
  height: 2.75px;
  x: 2.75px;
  y: 14.25px;
  rx: 1.25px;
}

.cnkmunb4t {
  d: path("M7.5 11.5c-1-1.1-1-2.15 0-3.25s1-2.15 0-3.25s-1-1.5-.25-2.25M12 11.5c-1-1.1-1-2.15 0-3.25S13 6.1 12 5s-1-1.5-.25-2.25m4.75 8.75c-1-1.1-1-2.15 0-3.25s1-2.15 0-3.25s-1-1.5-.25-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
