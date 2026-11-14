<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri309ebfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:undershirt" /></template>
<style>
.ri309ebfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.5V5c0 3-2.25 4.5-2.25 7v9.5h15V12c0-2.5-2.25-4-2.25-7V2.5h-3c0 6-4.5 6-4.5 0Zm-2.25 16h15");
}

</style>
