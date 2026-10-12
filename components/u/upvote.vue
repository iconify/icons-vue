<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z_-i5x3fo"/><path class="fzfa9xrtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:upvote" /></template>
<style>
.fzfa9xrtu {
  d: path("M9.75 15.5L12 13.25l2.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_-i5x3fo {
  d: path("m13.05 3.83l6.9 7.09Q21 12 19.5 12h-2Q16 12 16 13.5v6.25q0 1.5-1.5 1.5h-5q-1.5 0-1.5-1.5V13.5Q8 12 6.5 12h-2q-1.5 0-.45-1.08l6.9-7.09q1.05-1.08 2.1 0");
}

</style>
