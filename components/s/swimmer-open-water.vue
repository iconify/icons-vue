<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l0-69gb5e"/><path class="v7bhsfouk"/><path class="bsl0ynbqn"/><path class="zf65bnmhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swimmer-open-water" /></template>
<style>
.bsl0ynbqn {
  d: path("M2.5 15.5q2.75-2.5 5.5 0t5.5 0t5.5 0q1.25 1.25 2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0-69gb5e {
  d: path("M8.5 11.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.v7bhsfouk {
  d: path("M16.25 14.25C16.5 5.5 7 2.5 3.5 8.5");
}

.zf65bnmhy {
  d: path("M5 19.25q2.5-2 5 0t5 0t5 0");
}

</style>
