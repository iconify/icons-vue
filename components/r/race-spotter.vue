<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l539_ragy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:race-spotter" /></template>
<style>
.l539_ragy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 8.5h.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 7.875 15.5h-.75A2.625 2.625 0 0 1 4.5 12.875v-1.75A2.625 2.625 0 0 1 7.125 8.5m9 0h.75a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625h-.75a2.625 2.625 0 0 1-2.625-2.625v-1.75A2.625 2.625 0 0 1 16.125 8.5M10.5 12h3M8 8.5a4.25 4.25 0 1 1 8 0m-12 13c0-2 3.5-3.25 8-3.25s8 1.25 8 3.25");
}

</style>
