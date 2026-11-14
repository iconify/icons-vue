<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mts5qhblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toilet-lid-open" /></template>
<style>
.mts5qhblx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3H9v8H3.5Zm0 8h17c0 3.5-2.5 6-6.25 6.25L15 21H8.5l.75-4.25C5.75 16 3.5 14 3.5 11ZM11 3v5.5");
}

</style>
