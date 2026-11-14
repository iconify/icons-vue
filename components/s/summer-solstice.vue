<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj4-v4b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:summer-solstice" /></template>
<style>
.aj4-v4b5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 12.25a4.75 4.75 0 0 1 9.5 0m-13.25 0h12.7m5.6 0h.7m-10.5-7v-2m-5 4L4.75 6M16 7.25L17.25 6M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
