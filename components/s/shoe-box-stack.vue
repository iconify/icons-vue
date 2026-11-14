<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu8zxk_gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shoe-box-stack" /></template>
<style>
.zu8zxk_gu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 15.5h16a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20v-3A1.5 1.5 0 0 1 4 15.5m1-6h14a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 14v-3A1.5 1.5 0 0 1 5 9.5m1.5-6h11A1.5 1.5 0 0 1 19 5v3a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 8V5a1.5 1.5 0 0 1 1.5-1.5m-4 14.25h19m-18-6h17M5 5.75h14");
}

</style>
