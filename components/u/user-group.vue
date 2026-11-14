<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyrkgk6_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:user-group" /></template>
<style>
.fyrkgk6_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5c0-2.75 1.75-4.75 4-4.75s4 2 4 4.75c0 .6-.4 1-1 1h-6c-.6 0-1-.4-1-1m11 0c0-2.75 1.75-4.75 4-4.75s4 2 4 4.75c0 .6-.4 1-1 1h-6c-.6 0-1-.4-1-1m-10-11a3 3 0 1 0 6 0a3 3 0 1 0-6 0m11 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
