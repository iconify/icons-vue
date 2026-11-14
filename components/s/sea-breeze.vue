<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3tij1egt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sea-breeze" /></template>
<style>
.p3tij1egt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h12.5a2.5 2.5 0 0 0 0-5M3 12h10a2.5 2.5 0 0 1 0 5M3 19.25q1.75-1.5 3.5 0t3.5 0m3.5.5h8m-2-2l2 2l-2 2");
}

</style>
