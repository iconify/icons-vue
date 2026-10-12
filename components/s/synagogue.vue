<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkclsnbiv"/><path class="ujpzdibug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:synagogue" /></template>
<style>
.bkclsnbiv {
  d: path("M2.75 21.25V7a2 2 0 0 1 4 0v4l4.7-4.25a.8.8 0 0 1 1.1 0l4.7 4.25V7a2 2 0 0 1 4 0v14.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ujpzdibug {
  d: path("m12 9l2.17 3.75H9.83Zm0 5l2.17-3.75H9.83Zm-1.5 7.25v-2.5a1.5 1.5 0 0 1 3 0v2.5");
}

</style>
