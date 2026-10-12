<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwkd7xbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pan-flute" /></template>
<style>
.bwkd7xbzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3h17q.75 0 .75.75v5q0 .75-.75.75h-2.2q-.75 0-.75.75v1.5q0 .75-.75.75h-2.2q-.75 0-.75.75v1.5q0 .75-.75.75h-2.2q-.75 0-.75.75v1.5q0 .75-.75.75H7.2q-.75 0-.75.75v1.25q0 .75-.75.75H3.5q-.75 0-.75-.75V3.75q0-.75.75-.75m-.75 3.75h18.5m-14.8 0V18.5m3.7-11.75v8.75m3.7-8.75v5.75m3.7-5.75V9.5");
}

</style>
