<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsklof32l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-vest" /></template>
<style>
.fsklof32l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.04 3.59l2.42 3.82q.54.84 1.08 0l2.42-3.82q.54-.84 1.54-.84h.5q1 0 1 1v2.5q0 1 .6 1.8l1.05 1.4q.6.8.6 1.8v9q0 1-1 1H4.75q-1 0-1-1v-9q0-1 .6-1.8l1.05-1.4q.6-.8.6-1.8v-2.5q0-1 1-1h.5q1 0 1.54.84M12 8.25v13m-8.25-6h16.5");
}

</style>
