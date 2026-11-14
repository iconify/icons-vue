<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpr6ahmgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wall-planter" /></template>
<style>
.cpr6ahmgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5zA1.75 1.75 0 0 1 6 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 4.25 2.5m3.5 10h11a1.75 1.75 0 0 1 1.75 1.75v2.5a1.75 1.75 0 0 1-1.75 1.75h-11A1.75 1.75 0 0 1 6 16.75v-2.5a1.75 1.75 0 0 1 1.75-1.75M6 21.5l4-3m3.25-6V5m0 5C10.5 10 9 8.5 9 6c2.75 0 4.25 1.5 4.25 4m0-1C16 9 17.5 7.5 17.5 5c-2.75 0-4.25 1.5-4.25 4");
}

</style>
