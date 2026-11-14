<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_t9o6y0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:previous-track" /></template>
<style>
.c_t9o6y0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.111 8.476l-2.561 2.195a1.75 1.75 0 0 0 0 2.658l2.561 2.195A1.75 1.75 0 0 0 21 14.195v-4.39a1.75 1.75 0 0 0-2.889-1.329m-7.5 0L8.05 10.671a1.75 1.75 0 0 0 0 2.658l2.561 2.195a1.75 1.75 0 0 0 2.889-1.329v-4.39a1.75 1.75 0 0 0-2.889-1.329M3.5 6v12");
}

</style>
