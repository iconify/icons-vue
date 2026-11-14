<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op1so4vnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recycle-loop" /></template>
<style>
.op1so4vnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 10.5L12 4.75l3.5 6m.75-2.5l-.75 2.5L13 10m4 3.5l3.25 5.5H13.5m1.75-1.75L13.5 19l1.75 1.75M10.5 19H3.75l3.5-6m-2.5.75l2.5-.75l.75 2.5");
}

</style>
