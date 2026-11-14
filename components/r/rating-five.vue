<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpc3s-bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rating-five" /></template>
<style>
.dpc3s-bos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 7.25l1.616 3.025l3.377.603l-2.378 2.472l.471 3.397L8 15.25l-3.086 1.497l.471-3.397l-2.378-2.472l3.377-.603Zm12-.75h-4.5L15 11q1.125-.75 2.25-.75c1.75 0 3 1.25 3 3.25S18.75 17 17 17c-1.25 0-2.25-.5-2.75-1.5");
}

</style>
