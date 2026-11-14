<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lt_qb2bmg"/><path class="i6hh300fo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:project-phase" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i6hh300fo {
  d: path("M9.75 19.5v-10h4.5v10m-11.75 0h19m-4.5 0v-15h4.5v15");
}

.lt_qb2bmg {
  fill: currentColor;
  d: path("M4 14h1.5A1.5 1.5 0 0 1 7 15.5V18a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 18v-2.5A1.5 1.5 0 0 1 4 14");
}

</style>
