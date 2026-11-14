<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhh47gb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:staff-assisting" /></template>
<style>
.yhh47gb9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM2.5 21c0-4 2.5-6 6-6s6 2 6 6m1-17h5a1 1 0 0 1 1 1v4.5a1 1 0 0 1-1 1H17l-2.5 2V5a1 1 0 0 1 1-1Z");
}

</style>
