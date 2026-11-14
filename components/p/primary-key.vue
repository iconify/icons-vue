<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b638ro0xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:primary-key" /></template>
<style>
.b638ro0xu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m6 2.5L20 20m-4-4l2.5-2.5M18 18l2.5-2.5");
}

</style>
