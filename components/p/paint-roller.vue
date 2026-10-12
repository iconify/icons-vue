<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g95pgxbiv"/><path class="c5rin1bxc"/><rect class="gru5pbcnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paint-roller" /></template>
<style>
.c5rin1bxc {
  d: path("M17.75 5.75h1.5a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H12A1.25 1.25 0 0 0 10.75 13v1.75");
}

.g95pgxbiv {
  width: 15px;
  height: 6.25px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.gru5pbcnu {
  width: 3.5px;
  height: 6.75px;
  x: 9px;
  y: 14.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
