<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pot9ozz-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:muscle-strain" /></template>
<style>
.pot9ozz-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.97 20.5H2.5V15c0-2.181 1.057-3.701 2.786-4.368m5.86.683q.178.096.354.185l2-1.5l-.5-3.5c-.25-1.5.75-3 2.5-3h2c1.75 0 2.75 1.25 2.25 3l-1.5 5c-.75 3-1.75 5.5-4.25 7.25a10 10 0 0 1-.97.531M9 9l-1.25 3L10 14l-1.5 2.5l1.75 2.75L9.5 22");
}

</style>
