<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1zkf3bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tracking-camera" /></template>
<style>
.v1zkf3bne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 2.5h7.75A2.625 2.625 0 0 1 16 5.125v1.75A2.625 2.625 0 0 1 13.375 9.5h-7.75A2.625 2.625 0 0 1 3 6.875v-1.75A2.625 2.625 0 0 1 5.625 2.5M16 4l3.5-1v6L16 8M8.5 9.5v5H3M15 17v-2h2m3 0h2v2m0 3v2h-2m-3 0h-2v-2");
}

</style>
