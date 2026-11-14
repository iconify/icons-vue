<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="alcjcqb6l"/><path class="r22_p6otv"/><path class="w_gh_6bhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tree-cut" /></template>
<style>
.alcjcqb6l {
  d: path("M4.5 7.5a7.5 4 0 1 0 15 0a7.5 4 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r22_p6otv {
  d: path("M4.5 7.5V16c0 3.5-.5 5-2 5h19c-1.5 0-2-1.5-2-5V7.5");
}

.w_gh_6bhy {
  d: path("M8 7.5a4 1.25 0 1 0 8 0a4 1.25 0 1 0-8 0M9 21c.5-1.5.5-3 .5-4.5M15 21c-.5-1.5-.5-3-.5-4.5");
}

</style>
