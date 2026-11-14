<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9opcebfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:space-between" /></template>
<style>
.z9opcebfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3v18m19-18v18M7 6za1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 7 18a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 7 6m10 0za1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 17 18a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 17 6");
}

</style>
