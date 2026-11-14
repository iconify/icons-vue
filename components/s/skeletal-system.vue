<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i4seh8u-l"/><path class="iupddsb1l"/><path class="v320ucbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skeletal-system" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4seh8u-l {
  d: path("M11.436 19.5h-.186c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l2 2.5c.25 1-.25 1.5-1.25 1.5c-.75 0-1-.25-1.25-.75L12 12l.5 2l.397 2.25m-5.647-12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9 15.5l3.5-3.5m-5.5 3.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.iupddsb1l {
  d: path("M15.5 20.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0m3-5.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.v320ucbgg {
  d: path("M19.75 16.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
