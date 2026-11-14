<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e1b69obhg"/><path class="zxw2_6bqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roundabout-exit-right" /></template>
<style>
.e1b69obhg {
  d: path("M10 21.5v-7a5 5 0 0 0 5-5h4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxw2_6bqs {
  d: path("m17.5 7.25l2.25 2.25l-2.25 2.25M10 14.5a5 5 0 1 1 4-8");
}

</style>
