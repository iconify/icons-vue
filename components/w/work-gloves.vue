<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3--yveox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:work-gloves" /></template>
<style>
.w3--yveox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 15.5V12L5.6 9.35a1.5 1.5 0 0 1 2.12-2.12l.53.52V5a2.25 2.25 0 0 1 2.25-2.25h4A2.25 2.25 0 0 1 16.75 5v10.5Zm3-12.75v4m2.5-4v4m-4.5 8.75h6.5q1 0 1.21.98l.83 3.79q.21.98-.79.98H8q-1 0-.79-.98l.83-3.79q.21-.98 1.21-.98");
}

</style>
