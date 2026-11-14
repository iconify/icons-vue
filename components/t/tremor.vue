<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zik2ptbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tremor" /></template>
<style>
.zik2ptbxq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 12v3.5c0 3.25-2.25 6-5.25 6c-2.75 0-4.25-1.25-5.5-3.25l-2.5-3.75c-.5-1 0-2 1-2.25c.75-.25 1.5.25 2 1l2 2.25v-4m0 0V6m3 5V4m3 7V4.75M17 12V7.25M20 6c1 1.5 1 3.5 0 5m.5 3c.75 1 .75 2.25 0 3.25M3.5 4.5c-1 1.5-1 3.5 0 5");
}

</style>
