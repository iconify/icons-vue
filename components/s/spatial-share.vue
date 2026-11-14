<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zspv19ouc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spatial-share" /></template>
<style>
.zspv19ouc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.875 2.5h6.25A4.375 4.375 0 0 1 17.5 6.875v2.75A4.375 4.375 0 0 1 13.125 14h-6.25A4.375 4.375 0 0 1 2.5 9.625v-2.75A4.375 4.375 0 0 1 6.875 2.5M19.25 14.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-5 3.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 2.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-2.75-3.5l3-1.75m-3 3.25l3 1.25");
}

</style>
