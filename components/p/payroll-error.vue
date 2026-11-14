<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhr4i7bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:payroll-error" /></template>
<style>
.zhr4i7bhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.25 3.5l-2 5l2.5 4l-2.25 3.75l.75 4.25a8.5 8.5 0 0 1 1-17m2.5 0l-2 5l2.5 4L12 16.25l.75 4.25a8.5 8.5 0 0 0 1-17M6 10v4");
}

</style>
