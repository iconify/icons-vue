<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e51-irdiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sequence-diagram" /></template>
<style>
.e51-irdiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h2.5A1.75 1.75 0 0 1 8.5 4.25v1A1.75 1.75 0 0 1 6.75 7h-2.5A1.75 1.75 0 0 1 2.5 5.25v-1A1.75 1.75 0 0 1 4.25 2.5m13 0h2.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 7h-2.5a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75M5.5 7v14.5M18.5 7v14.5m-13-9h13m-2.75-2.75l2.75 2.75l-2.75 2.75m2.75 3.25h-13m2.75-2.75L5.5 18.5l2.75 2.75");
}

</style>
