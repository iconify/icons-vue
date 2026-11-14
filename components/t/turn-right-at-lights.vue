<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o0vz28bru"/><path class="ati25bcor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:turn-right-at-lights" /></template>
<style>
.ati25bcor {
  d: path("M18.25 7.25L21 10l-2.75 2.75M6 2.5za3 3 0 0 1 3 3V12a3 3 0 0 1-3 3a3 3 0 0 1-3-3V5.5a3 3 0 0 1 3-3m0 3h.01M6 8.75h.01M6 12h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o0vz28bru {
  d: path("M13 21.5v-8a3.5 3.5 0 0 1 3.5-3.5H21");
}

</style>
