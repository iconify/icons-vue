<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4r5-8i9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oil-rig-offshore" /></template>
<style>
.s4r5-8i9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18v3H3Zm5 0l2.5-8.5L13 11m-7.5 3v7.5m13-7.5v7.5M15 7.5h4.5V11H15Zm-6 0h3M8 18q1-1 2 0t2 0t2 0t2 0");
}

</style>
