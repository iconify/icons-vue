<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-yqoe09g"/><path class="gt9cu5ddg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:volunteer-availability" /></template>
<style>
.gt9cu5ddg {
  d: path("m8.5 15.25l2.5 2.5l4.5-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-yqoe09g {
  d: path("M7.875 4.5h8.25A4.375 4.375 0 0 1 20.5 8.875v7.75A4.375 4.375 0 0 1 16.125 21h-8.25A4.375 4.375 0 0 1 3.5 16.625v-7.75A4.375 4.375 0 0 1 7.875 4.5M3.5 9.5h17M8 2.5v4m8-4v4");
}

</style>
