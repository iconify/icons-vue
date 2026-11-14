<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5e630bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mower-striping" /></template>
<style>
.y5e630bzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.726 6.5h8.548a1.75 1.75 0 0 1 1.645 1.152l2.727 7.5a1.75 1.75 0 0 1-1.644 2.348H4.998a1.75 1.75 0 0 1-1.644-2.348l2.727-7.5A1.75 1.75 0 0 1 7.726 6.5m2.524 0l-1.5 11m5-11l1.5 11");
}

</style>
