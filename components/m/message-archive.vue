<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfcig3_px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:message-archive" /></template>
<style>
.jfcig3_px {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11h15.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H4.25a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 4.25 11M4 14.5v5a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-5m-10 3.25h4M8.5 2.5h7A1.5 1.5 0 0 1 17 4v1.5A1.5 1.5 0 0 1 15.5 7h-4L10 8.25V7H8.5A1.5 1.5 0 0 1 7 5.5V4a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
