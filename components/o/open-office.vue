<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-pozfq4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-office" /></template>
<style>
.i-pozfq4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 3h4.5A1.75 1.75 0 0 1 16 4.75v14.5A1.75 1.75 0 0 1 14.25 21h-4.5A1.75 1.75 0 0 1 8 19.25V4.75A1.75 1.75 0 0 1 9.75 3M4 4.75zA1.25 1.25 0 0 1 5.25 6v1A1.25 1.25 0 0 1 4 8.25A1.25 1.25 0 0 1 2.75 7V6A1.25 1.25 0 0 1 4 4.75m0 5.5za1.25 1.25 0 0 1 1.25 1.25v1A1.25 1.25 0 0 1 4 13.75a1.25 1.25 0 0 1-1.25-1.25v-1A1.25 1.25 0 0 1 4 10.25m0 5.5zA1.25 1.25 0 0 1 5.25 17v1A1.25 1.25 0 0 1 4 19.25A1.25 1.25 0 0 1 2.75 18v-1A1.25 1.25 0 0 1 4 15.75m16-11zA1.25 1.25 0 0 1 21.25 6v1A1.25 1.25 0 0 1 20 8.25A1.25 1.25 0 0 1 18.75 7V6A1.25 1.25 0 0 1 20 4.75m0 5.5za1.25 1.25 0 0 1 1.25 1.25v1A1.25 1.25 0 0 1 20 13.75a1.25 1.25 0 0 1-1.25-1.25v-1A1.25 1.25 0 0 1 20 10.25m0 5.5zA1.25 1.25 0 0 1 21.25 17v1A1.25 1.25 0 0 1 20 19.25A1.25 1.25 0 0 1 18.75 18v-1A1.25 1.25 0 0 1 20 15.75");
}

</style>
