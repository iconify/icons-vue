<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-_pumgnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payroll-error" /></template>
<style>
.e-_pumgnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.25 3.5l-2 5l2.5 4l-2.25 3.75l.75 4.25a8.5 8.5 0 0 1 1-17Zm2.5 0l-2 5l2.5 4L12 16.25l.75 4.25a8.5 8.5 0 0 0 1-17ZM6 10v4");
}

</style>
