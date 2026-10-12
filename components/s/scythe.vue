<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7hu_dbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scythe" /></template>
<style>
.j7hu_dbwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 2.75C14.25 6 15.75 8.5 13 12s-4 3.25-4 5.75M14 5l2.5 1m-5.75 5.25l2.5 1M9 17.75c-2.5-.5-5 1-6.25 3.25C5 20.25 7 20.5 9 21.25Z");
}

</style>
