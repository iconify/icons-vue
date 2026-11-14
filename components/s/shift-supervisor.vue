<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_p2eyb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shift-supervisor" /></template>
<style>
.e_p2eyb1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5h1.5a4 4 0 0 1 8 0H16Zm2 0v2a3.5 3.5 0 0 0 7 0v-2M3 21c0-3.5 3.5-6 7.5-6c1.23 0 2.412.236 3.461.665M18 16h2a1.75 1.75 0 0 1 1.75 1.75V20A1.75 1.75 0 0 1 20 21.75h-2A1.75 1.75 0 0 1 16.25 20v-2.25A1.75 1.75 0 0 1 18 16m-.25 0h2.5M18 19h2");
}

</style>
