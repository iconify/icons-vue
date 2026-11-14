<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwwq8120r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:teachers-day-apple" /></template>
<style>
.iwwq8120r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5c-2-2-8.5-2-8.5 4c0 5.5 4 9 6.5 9c1 0 1.25-.5 2-.5s1 .5 2 .5c2.5 0 6.5-3.5 6.5-9c0-6-6.5-6-8.5-4m0 0v-5m0 1.25C13 3 15.25 2.5 17.5 3c-.75 1.5-3 2.25-5.5 1.75");
}

</style>
