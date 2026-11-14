<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8xvjuzel"/><path class="mpf6no7ir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:queue-add" /></template>
<style>
.c8xvjuzel {
  d: path("M10.5 7h7a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 7 17.5v-7A3.5 3.5 0 0 1 10.5 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpf6no7ir {
  d: path("M3 16V5a2 2 0 0 1 2-2h11m-2 7.5v7M10.5 14h7");
}

</style>
