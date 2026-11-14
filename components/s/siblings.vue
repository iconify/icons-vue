<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vifjv0dlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:siblings" /></template>
<style>
.vifjv0dlh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1 17v-9.25a3 3 0 0 1 6 0v9.25M14.5 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0M14 21.5v-3.25a2.5 2.5 0 0 1 5 0v3.25");
}

</style>
