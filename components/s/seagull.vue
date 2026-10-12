<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqqpi8bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seagull" /></template>
<style>
.bqqpi8bge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.5c2.75-2 6-1.5 8 1.5L12 12.75L13.25 11c2-3 5.25-3.5 8-1.5c-2.5.25-4.5 1.5-6 3.5l-2 2.5c-.75.75-1.75.75-2.5 0l-2-2.5c-1.5-2-3.5-3.25-6-3.5m0 10.25C4 19.75 4 19 5.25 19s1.25.75 2.5.75S9 19 10.25 19s1.25.75 2.5.75S14 19 15.25 19s1.25.75 2.5.75S19 19 20.25 19");
}

</style>
