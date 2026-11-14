<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuvaxdbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:record-edit" /></template>
<style>
.wuvaxdbcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.6 12.5H2.5V5h19v7.5h-.1M8.5 5v7.5m6-7.5v7.5m7 4l-4.25 4.25l-2.5.5l.5-2.5l4.25-4.25l2 2m-6.25 2.25l2 2");
}

</style>
