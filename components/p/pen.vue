<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ut-ricb-u"/><path class="ypz0b4l9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ut-ricb-u {
  d: path("m20.31 5.46l-1.77-1.77q-.71-.71-1.42 0l-8.48 8.48q-.71.71 0 1.42l1.77 1.77q.71.71 1.42 0l8.48-8.48q.71-.71 0-1.42");
}

.ypz0b4l9p {
  d: path("M10.7 15.65L8.35 13.3q-.42-.42-.73.09l-2.31 3.83q-.31.51.11.93l.43.43q.42.42.93.11l3.83-2.31q.51-.31.09-.73m5.37-4.53l-3.19-3.19");
}

</style>
