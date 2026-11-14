<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l6sg9wxuy"/><path class="gvfueab3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shoplifting-alert" /></template>
<style>
.gvfueab3v {
  d: path("M5.75 10.75a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0m8.5 0a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0M3.5 9.5l-1.5 4m18.5-4l1.25 2.5M18 14.5V18m0 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6sg9wxuy {
  d: path("M15.174 14.848C13.846 14.467 13.004 13.5 12 13.5c-1.25 0-2.25 1.5-4.25 1.5c-2.25 0-4.25-1.25-4.25-3.5V8C7 6.5 17 6.5 20.5 8v3.5c0 .502-.1.954-.279 1.354");
}

</style>
