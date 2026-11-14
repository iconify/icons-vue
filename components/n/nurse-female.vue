<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwdyqlgjv"/><path class="dj2f7lbwd"/><path class="zyodz0bmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nurse-female" /></template>
<style>
.dj2f7lbwd {
  fill: currentColor;
  d: path("m8 5.5l.75-3h6.5l.75 3c-2.5 1-5.5 1-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwdyqlgjv {
  d: path("M4 20c0-3.25 3.5-5.5 8-5.5s8 2.25 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.zyodz0bmo {
  d: path("M8.25 8C7 10 7 13 7.75 15.5m8-7.5c1.25 2 1.25 5 .5 7.5");
}

</style>
