<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbmf7yfgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:report-binder" /></template>
<style>
.nbmf7yfgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5h6A3.5 3.5 0 0 1 19.5 6v12a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 6.5 18V6A3.5 3.5 0 0 1 10 2.5m-7 4h6.25M3 12h6.25M3 17.5h6.25m3.25-2V13m2.5 2.5V9m2.5 6.5V11");
}

</style>
