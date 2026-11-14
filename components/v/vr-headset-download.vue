<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl6ezr2-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-download" /></template>
<style>
.yl6ezr2-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14a2.5 2.5 0 0 1 2.5 2.5v4A2.5 2.5 0 0 1 19 12h-3.75L14 9.75a2 2 0 0 0-4 0L8.75 12H5a2.5 2.5 0 0 1-2.5-2.5v-4A2.5 2.5 0 0 1 5 3m13 12v6.5m-2.75-2.75L18 21.5l2.75-2.75");
}

</style>
