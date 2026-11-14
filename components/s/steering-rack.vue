<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffkcg4bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:steering-rack" /></template>
<style>
.ffkcg4bmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 7.5h7.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 15.75 12h-7.5a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 8.25 7.5m-.75 0l1.5-3l1.5 3l1.5-3l1.5 3l1.5-3l1.5 3m-10 3l-1.25 4.75M17.5 10.5l1.25 4.75M2.5 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0m15 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
