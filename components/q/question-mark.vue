<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0-n3yb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:question-mark" /></template>
<style>
.v0-n3yb1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8c0-2.75 2.1-4.5 4.5-4.5c2.6 0 4.5 1.75 4.5 4.25C16.5 11 12 11.5 12 15m0 4.5h.01");
}

</style>
