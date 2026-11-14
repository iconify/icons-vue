<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7ssfbchu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:well-water" /></template>
<style>
.n7ssfbchu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7.5h1.5A1.75 1.75 0 0 1 12 9.25v10.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 7 19.75V9.25A1.75 1.75 0 0 1 8.75 7.5m-1.5-2h4.5a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-4.5a1 1 0 0 1-1-1a1 1 0 0 1 1-1m4.75 4h5v2m-9.5-6L3 2.5m1.5 19h10m2.5-8c1 1.5 1.5 2.25 1.5 3a1.5 1.5 0 0 1-3 0c0-.75.5-1.5 1.5-3");
}

</style>
