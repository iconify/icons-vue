<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvmmc6b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-pit-benches" /></template>
<style>
.vvmmc6b-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5L3 8.5h1.75l.5 3.5H7l.5 3.5h1.75l.5 3.5h4.5l.5-3.5h1.75L17 12h1.75l.5-3.5H21l.5-3.5");
}

</style>
