<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqyohyboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voicemail-play" /></template>
<style>
.mqyohyboi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 8.75a3.25 3.25 0 1 0 0 6.5a3.25 3.25 0 0 0 0-6.5m10.5 0a3.25 3.25 0 1 0 0 6.5a3.25 3.25 0 0 0 0-6.5m-10.5 6.5h10.5");
}

</style>
