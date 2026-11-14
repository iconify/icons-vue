<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u2kellbrr"/><path class="vtl22d9bc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wedding-bells" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u2kellbrr {
  d: path("M3.25 19.5c1.25-1 1.25-3 1.25-6v-2.75a2.25 2.25 0 0 1 4.5 0v2.75c0 3 0 5 1.25 6Zm10.5 0c1.25-1 1.25-3 1.25-6v-2.75a2.25 2.25 0 0 1 4.5 0v2.75c0 3 0 5 1.25 6Z");
}

.vtl22d9bc {
  d: path("m6.75 8.5l2.75-3v-3l5 3l2.75 3m-2.75-3v-3l-5 3m-4 14a1.25 1.25 0 0 0 2.5 0m8 0a1.25 1.25 0 0 0 2.5 0");
}

</style>
