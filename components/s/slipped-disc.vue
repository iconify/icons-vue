<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpz6bhbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:slipped-disc" /></template>
<style>
.jpz6bhbzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3h7.75A2.625 2.625 0 0 1 16 5.625v.75A2.625 2.625 0 0 1 13.375 9h-7.75A2.625 2.625 0 0 1 3 6.375v-.75A2.625 2.625 0 0 1 5.625 3m0 12h7.75A2.625 2.625 0 0 1 16 17.625v.75A2.625 2.625 0 0 1 13.375 21h-7.75A2.625 2.625 0 0 1 3 18.375v-.75A2.625 2.625 0 0 1 5.625 15M16 5l3 1m-3 13l3-1M4.5 10.75H15c3.5 0 6.5.5 6.5 1.25s-3 1.25-6.5 1.25H4.5c-.75 0-1-.5-1-1.25s.25-1.25 1-1.25");
}

</style>
