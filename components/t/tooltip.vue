<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h42bdubtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooltip" /></template>
<style>
.h42bdubtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4h15a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2h-5l-2.5 3l-2.5-3h-5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2M7 10.25h10");
}

</style>
