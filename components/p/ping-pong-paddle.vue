<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ost_9eacq"/><path class="pkc3vy4-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ping-pong-paddle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ost_9eacq {
  d: path("M8 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

.pkc3vy4-e {
  d: path("M9.879 14.121za1.5 1.5 0 0 1 0 2.122l-2.475 2.475a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l2.475-2.475a1.5 1.5 0 0 1 2.122 0M16.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
