<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-iwj4bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sedge-grass" /></template>
<style>
.k-iwj4bap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 20.5Q5.5 14 2.5 10M9 20.5Q8.5 11 6.5 4M12 20.5v-18m3 18Q15.5 11 17.5 4m.5 16.5q.5-6.5 3.5-10.5m-18 10.5h17");
}

</style>
