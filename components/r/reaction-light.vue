<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s21q82glx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reaction-light" /></template>
<style>
.s21q82glx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5 5v3.5m-3.5 0h7M12 2.25v3M6.5 7.5l-2-2m13 2l2-2");
}

</style>
