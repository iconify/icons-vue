<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j6s7l6bxz"/><path class="ny6m15pqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swim-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6s7l6bxz {
  d: path("M8 7c-5 3-4.5 14 0 14h8c4.5 0 5-11 0-14Zm2 0L8.5 3h7L14 7");
}

.ny6m15pqj {
  d: path("M7.5 14q2.25-1.5 4.5 0t4.5 0");
}

</style>
