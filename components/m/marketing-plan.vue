<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cw_5t-biy"/><path class="zjf48bbgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marketing-plan" /></template>
<style>
.cw_5t-biy {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v7.75A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-7.75A4.375 4.375 0 0 1 7.375 4.5M3 9.5h18m-13-7v4m8-4v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zjf48bbgq {
  d: path("M9.5 18v-5.75H15L13.5 14l1.5 1.75H9.5");
}

</style>
