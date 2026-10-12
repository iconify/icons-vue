<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="a4b16elmh"/><path class="h2pi5or3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sound-trend" /></template>
<style>
.a4b16elmh {
  cx: 7px;
  cy: 17.75px;
  r: 3.25px;
}

.h2pi5or3k {
  d: path("M10.25 17.75v-14l4.5 1.75M13.25 18l3-3.25l2 2l3-3.5m-2.75 0h2.75V16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
