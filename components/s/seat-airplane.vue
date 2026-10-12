<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4pt6scal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seat-airplane" /></template>
<style>
.h4pt6scal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.75h1.5q1.25 0 1.52 1.22l1.71 7.56q.27 1.22 1.52 1.22H19q1.25 0 1.25 1.25v1.5q0 1.25-1.25 1.25H9.75q-1.25 0-1.57-1.21L5.07 3.96Q4.75 2.75 6 2.75m-.31 3.5h3.85m4.96 10.5v4.5m-3 0h6");
}

</style>
