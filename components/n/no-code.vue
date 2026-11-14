<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agr2x9bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-code" /></template>
<style>
.agr2x9bfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5L3 7l4 4.5m10-9L21 7l-4 4.5m-4-9l-2 9m3.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m1 2.5l5-5");
}

</style>
