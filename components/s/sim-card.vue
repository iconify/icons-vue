<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x6ylc1bzr"/><rect class="s7zx8eu9x"/><path class="jr6q5hbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sim-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jr6q5hbss {
  d: path("M8.75 14.25h6.5");
}

.s7zx8eu9x {
  width: 6.5px;
  height: 7px;
  x: 8.75px;
  y: 10.75px;
  rx: 1px;
}

.x6ylc1bzr {
  d: path("M7.75 2.75h6.5l4.5 4.5v11.5a2.5 2.5 0 0 1-2.5 2.5h-8.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
