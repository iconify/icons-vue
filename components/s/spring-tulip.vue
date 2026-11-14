<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8b0uglpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spring-tulip" /></template>
<style>
.w8b0uglpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 4l2.25 2.5l2.25-3l2.25 3L16.5 4v4.5a4.5 4.5 0 0 1-9 0Zm4.5 9v8.5m0-1.5c-4-.5-6-3-6-6c3 .5 5.5 2.5 6 6m0 0c4-.5 6-3 6-6c-3 .5-5.5 2.5-6 6");
}

</style>
