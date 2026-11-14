<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2al0qu5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mandatory-hairnet" /></template>
<style>
.f2al0qu5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9.5c-2-2.5 0-6 3-5.5c1-2 6-2 7 0c3-.5 5 3 3 5.5Zm1.5 0v1a5 5 0 0 0 10 0v-1m-13 12c0-1.75 3.5-3.25 8-3.25s8 1.5 8 3.25");
}

</style>
