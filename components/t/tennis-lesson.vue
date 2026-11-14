<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="payuzpbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tennis-lesson" /></template>
<style>
.payuzpbrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6a3.25 3.25 0 1 0 6.5 0A3.25 3.25 0 1 0 4 6M2.5 18c0-3.5 2.25-5.75 4.75-5.75S12 14.5 12 18m3.5-8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-.75 8c0-2 1.25-2.75 3.25-2.75s3.25.75 3.25 2.75M2.5 21h19");
}

</style>
