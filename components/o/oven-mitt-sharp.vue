<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf0jz4bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oven-mitt-sharp" /></template>
<style>
.wf0jz4bht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.25 16.25V8.5a4.75 4.75 0 0 0-9.5 0v1.6L6.6 8.7a1.9 1.9 0 0 0-2.4 2.9l4.55 4.65Zm-7-6.25h4M7.5 18.5H19v2.75H7.5z");
}

</style>
