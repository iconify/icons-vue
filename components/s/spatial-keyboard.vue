<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jslzlrq-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spatial-keyboard" /></template>
<style>
.jslzlrq-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.55 6h10.588a2.625 2.625 0 0 1 2.547 3.262l-1.688 6.75A2.625 2.625 0 0 1 16.45 18H5.862a2.625 2.625 0 0 1-2.547-3.262l1.688-6.75A2.625 2.625 0 0 1 7.55 6m-.05 4H9m2.75 0h1.5M16 10h1.5m-11 4H8m2.75 0h1.5M15 14h1.5");
}

</style>
