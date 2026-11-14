<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b67t7ya8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:maintenance-mode" /></template>
<style>
.b67t7ya8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 6.5h13.75A2.625 2.625 0 0 1 21.5 9.125v1.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 10.875v-1.75A2.625 2.625 0 0 1 5.125 6.5m.875 7V21m12-7.5V21M6 3v3.5M18 3v3.5m-9 7l2.5-7m1 7l2.5-7");
}

</style>
