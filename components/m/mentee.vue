<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb9f1g6ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mentee" /></template>
<style>
.nb9f1g6ru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c0-3 2.75-5 6-5s6 2 6 5Zm2.75-12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M18.5 21v-8m0 2.5c-2 0-2.75-1.25-2.75-2.75c1.75 0 2.75 1 2.75 2.75m0-2.5c0-2 1-3.25 2.75-3.25c0 2-1 3.25-2.75 3.25");
}

</style>
