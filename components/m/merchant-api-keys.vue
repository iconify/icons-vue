<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpli2wr1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:merchant-api-keys" /></template>
<style>
.zpli2wr1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16a4 4 0 1 0 8 0a4 4 0 1 0-8 0m6.75-2.75L19.5 3.5M17 6l2.25 2.25m-4.75.25l1.75 1.75M16.5 15L14 18l2.5 3m3-6l2.5 3l-2.5 3");
}

</style>
