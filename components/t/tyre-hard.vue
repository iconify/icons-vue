<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dj8l18b2n"/><path class="tknrb0bwh"/><path class="ghbstfbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tyre-hard" /></template>
<style>
.dj8l18b2n {
  d: path("M2.5 12a7.5 9.5 0 1 0 15 0a7.5 9.5 0 1 0-15 0");
}

.ghbstfbku {
  d: path("M7.25 12a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0m-1.5-3.5a5 7 0 0 0 0 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tknrb0bwh {
  d: path("M10 2.5h3a7.5 9.5 0 0 1 0 19h-3");
}

</style>
