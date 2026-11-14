<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4alcz5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:suction-power" /></template>
<style>
.fv4alcz5s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.5h16V18a2 2 0 0 0-2-2h-4v-3.5h-4V16H6a2 2 0 0 0-2 2Zm8-18V8m-1.75-1.75L12 8l1.75-1.75M3.5 4.5l4 4m-3 0h3v-3m13-1l-4 4m3 0h-3v-3");
}

</style>
