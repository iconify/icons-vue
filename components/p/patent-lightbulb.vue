<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8liiu0mo"/><path class="jmr67kjph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patent-lightbulb" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmr67kjph {
  d: path("M10.25 12v-1.5L12 8.75l1.75 1.75V12");
}

.m8liiu0mo {
  d: path("M9 15v-1.5c-2-1.25-3-3-3-5a6 6 0 0 1 12 0c0 2-1 3.75-3 5V15Zm0 0v6.5l3-2.25l3 2.25V15");
}

</style>
