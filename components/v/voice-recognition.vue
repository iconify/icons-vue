<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uid4csb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voice-recognition" /></template>
<style>
.uid4csb4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5V5A2.25 2.25 0 0 1 5 2.75h2.5m9 0H19A2.25 2.25 0 0 1 21.25 5v2.5m0 9V19A2.25 2.25 0 0 1 19 21.25h-2.5m-9 0H5A2.25 2.25 0 0 1 2.75 19v-2.5M7.5 10v4m3-6.5v9m3-7.5v6m3-4.25v2.5");
}

</style>
