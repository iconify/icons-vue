<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7ray43gz"/><path class="julv8sb5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outcrop" /></template>
<style>
.h7ray43gz {
  d: path("M3.5 20L6 12.5l4-3l3-5l4.5 3L20 20M2.5 20h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.julv8sb5z {
  d: path("m5 15.5l6-3h7.5");
}

</style>
