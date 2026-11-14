<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="og1-2jb_m"/><path class="dcgtcybty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:robot-vacuum-stuck" /></template>
<style>
.dcgtcybty {
  d: path("M6.525 8.025a3.5 3.5 0 0 1 5.856 1.569M18 14.5V18m0 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og1-2jb_m {
  d: path("M17.25 2.5h.5a1.75 1.75 0 0 1 1.75 1.75v5.5a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-5.5a1.75 1.75 0 0 1 1.75-1.75m-14.75 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

</style>
