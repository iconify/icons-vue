<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g0njtk0tw"/><path class="joz1zabqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rug" /></template>
<style>
.g0njtk0tw {
  width: 14.5px;
  height: 13.5px;
  x: 4.75px;
  y: 5.25px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.joz1zabqp {
  d: path("m12 8.5l3.5 3.5l-3.5 3.5L8.5 12ZM2.75 8h2m-2 4h2m-2 4h2m14.5-8h2m-2 4h2m-2 4h2");
}

</style>
