<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="orokcqbkr"/><path class="l-unlab0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rain-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-unlab0t {
  d: path("M9 12.5a2 2 0 0 1 0-4a3.25 3.25 0 0 1 6-.25a2.125 2.125 0 0 1 0 4.25Zm.5 2.5L9 16.5m3-1.5l-.5 1.5m3-1.5l-.5 1.5");
}

.orokcqbkr {
  d: path("M2.5 5h19v4.5a2.5 2.5 0 0 0 0 5V19h-19v-4.5a2.5 2.5 0 0 0 0-5Z");
}

</style>
