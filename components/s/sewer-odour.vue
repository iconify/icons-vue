<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8bm0zgjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sewer-odour" /></template>
<style>
.e8bm0zgjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 16a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m3-1.5h5m-5 3h5m-7-9.75q-1.25-1.25 0-2.5t0-2.5m4.5 5q-1.25-1.25 0-2.5t0-2.5m4.5 5q-1.25-1.25 0-2.5t0-2.5");
}

</style>
