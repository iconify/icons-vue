<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a55l47buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volcano-cross-section" /></template>
<style>
.a55l47buu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21L9 10l1.5 1.5h3L15 10l6.5 11Zm9.5-9.5V21m0-13.75V3M9 7L7.5 4.5M15 7l1.5-2.5");
}

</style>
