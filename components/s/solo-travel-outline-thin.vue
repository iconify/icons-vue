<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixfqlr8_d"/><path class="bgtqag34q"/><path class="jc4egvb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:solo-travel-outline-thin" /></template>
<style>
.bgtqag34q {
  d: path("M2 21a8 8 0 0 1 16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixfqlr8_d {
  d: path("M7 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.jc4egvb_a {
  d: path("M16 9h4v7h-4Z");
}

</style>
