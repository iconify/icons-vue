<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv8cvym3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rope-barrier" /></template>
<style>
.jv8cvym3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6v13.5M19.5 6v13.5m-15.882 2h1.764a.69.69 0 0 0 .618-1l-.085-.171a1.5 1.5 0 0 0-1.342-.829h-.146a1.5 1.5 0 0 0-1.342.829L3 20.5a.69.69 0 0 0 .618 1m15 0h1.764a.69.69 0 0 0 .618-1l-.085-.171a1.5 1.5 0 0 0-1.342-.829h-.146a1.5 1.5 0 0 0-1.342.829L18 20.5a.69.69 0 0 0 .618 1M3 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m15 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M4.5 7.5c2.5 8 12.5 8 15 0");
}

</style>
