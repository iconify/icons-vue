<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ucxu3gbut"/><path class="yta86jbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:placemat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ucxu3gbut {
  width: 18.5px;
  height: 14.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2.5px;
}

.yta86jbnf {
  d: path("M12 8.75a3.25 3.25 0 1 1 0 6.5a3.25 3.25 0 1 1 0-6.5m-6.25 0v6.5m12.5-6.5v6.5");
}

</style>
