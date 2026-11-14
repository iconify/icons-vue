<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gm5w2qmru"/><path class="bwzob6bne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tactics-board" /></template>
<style>
.bwzob6bne {
  d: path("M5 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m10.75-7.75l3 3m-3 0l3-3m-7.75 7l2.25-2.75m-2 .25l2-.25l-.25 2.25");
}

.gm5w2qmru {
  d: path("M6 2.5h12A3.5 3.5 0 0 1 21.5 6v8a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 14V6A3.5 3.5 0 0 1 6 2.5m1 15l-2 4m12-4l2 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
