<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gg_xxm92g"/><path class="h864w6bud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sdk" /></template>
<style>
.gg_xxm92g {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

.h864w6bud {
  d: path("M8.75 7.25v-2a1.5 1.5 0 0 1 1.5-1.5h3.5a1.5 1.5 0 0 1 1.5 1.5v2m-5.5 4.5l-2 2.25l2 2.25m4.5-4.5l2 2.25l-2 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
