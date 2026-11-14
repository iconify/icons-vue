<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h85re2k6v"/><path class="rvilz46-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sprint-launch" /></template>
<style>
.h85re2k6v {
  d: path("M20.5 3.5c-4.5 0-9 3-11.5 7l4.5 4.5c4-2.5 7-7 7-11.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rvilz46-b {
  d: path("M13.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-3.25 2.75L4.5 19.5l7.75-5.75M9.75 9.5H6.5l-2 2.5m10 2.25v3.25l-2.5 2");
}

</style>
