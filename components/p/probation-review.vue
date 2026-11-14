<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0saqdb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:probation-review" /></template>
<style>
.h0saqdb9g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.73 14.5h4.54a1.5 1.5 0 0 1 1.485 1.712l-.571 4A1.5 1.5 0 0 1 8.699 21.5H5.301a1.5 1.5 0 0 1-1.485-1.288l-.571-4A1.5 1.5 0 0 1 4.73 14.5m8.02-4.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m6.5 2.75L21.5 15M7 14.5V9m0 1c0-2 1.5-3.5 3.5-3.5C10.5 8.5 9 10 7 10m0 1.5c0-1.75-1.5-3-3.5-3c0 1.75 1.5 3 3.5 3");
}

</style>
