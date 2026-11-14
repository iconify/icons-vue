<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi_kqjbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spa-treatment" /></template>
<style>
.wi_kqjbty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 17.5h12.5A1.75 1.75 0 0 1 20 19.25A1.75 1.75 0 0 1 18.25 21H5.75A1.75 1.75 0 0 1 4 19.25a1.75 1.75 0 0 1 1.75-1.75M8 13h8a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 16 16H8a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 8 13m2.25-4h3.5A1.25 1.25 0 0 1 15 10.25a1.25 1.25 0 0 1-1.25 1.25h-3.5A1.25 1.25 0 0 1 9 10.25A1.25 1.25 0 0 1 10.25 9M12 7c-2.5-.5-2.5-3.5 0-4.5c2.5 1 2.5 4 0 4.5");
}

</style>
