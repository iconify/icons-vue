<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1x3iynuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-boarding" /></template>
<style>
.v1x3iynuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.375 2.5h4.75A4.375 4.375 0 0 1 16.5 6.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-4.75A4.375 4.375 0 0 1 3 13.125v-6.25A4.375 4.375 0 0 1 7.375 2.5M3 10.5h13.5m-6.75-8v8m-3.25 7v3m6.5-3v3m9-1.25h-5.5m2.5-2.5l-2.5 2.5l2.5 2.5");
}

</style>
