<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h1f02n4hn"/><path class="jwwz0nbrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tv-off" /></template>
<style>
.h1f02n4hn {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 6.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwwz0nbrh {
  d: path("M8.25 2.75L12 6.25l3.75-3.5m-7.5 18.5h7.5");
}

</style>
