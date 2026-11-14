<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzcj78biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:operating-table" /></template>
<style>
.qzcj78biz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 11H4.25A1.75 1.75 0 0 1 2.5 9.25A1.75 1.75 0 0 1 4.25 7.5M11.5 11h1a1.5 1.5 0 0 1 1.5 1.5V17a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 17v-4.5a1.5 1.5 0 0 1 1.5-1.5m-4 7.5h9A1.5 1.5 0 0 1 18 20a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 20a1.5 1.5 0 0 1 1.5-1.5m.5-11V11");
}

</style>
