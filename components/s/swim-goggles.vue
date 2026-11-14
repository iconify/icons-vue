<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-m4dj55x"/><path class="b1b3qo53v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swim-goggles" /></template>
<style>
.b1b3qo53v {
  d: path("M3.75 14.5c0-9.5 16.5-9.5 16.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-m4dj55x {
  d: path("M3.75 14.5a3.5 3 0 1 0 7 0a3.5 3 0 1 0-7 0m9.5 0a3.5 3 0 1 0 7 0a3.5 3 0 1 0-7 0m-2.5 0h2.5");
}

</style>
