<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufxgc78fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:zen-stones" /></template>
<style>
.ufxgc78fu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 16.5a7 2.75 0 1 0 14 0a7 2.75 0 1 0-14 0Zm2-5.25a5 2.25 0 1 0 10 0a5 2.25 0 1 0-10 0ZM8.75 7a3.25 1.75 0 1 0 6.5 0a3.25 1.75 0 1 0-6.5 0Z");
}

</style>
