<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of92pq_ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:watering-can-pouring" /></template>
<style>
.of92pq_ve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 9h4.75A2.625 2.625 0 0 1 13 11.625v5.75A2.625 2.625 0 0 1 10.375 20h-4.75A2.625 2.625 0 0 1 3 17.375v-5.75A2.625 2.625 0 0 1 5.625 9M5 9V6.5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2V9m2 7l6-7.5M17.5 7l3 3m.5 3.5h.01m-2.01 3h.01");
}

</style>
