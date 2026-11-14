<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6pjglb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:private-beach" /></template>
<style>
.d6pjglb-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.71 15.5H8L2.5 5L5 4l4.5 8.5h5.19m-6.19 3l-2 6m8-4h7v4.25h-7Zm1.5 0V16a2 2 0 0 1 4 0v1.5");
}

</style>
