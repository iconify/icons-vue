<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shfmmc8nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-strong" /></template>
<style>
.shfmmc8nz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.617 16.835L12 13.75c-.25-1-2.75-1-3 0l-.75 3.75C8 19 6.25 19 6 17.5L5.25 13c-.5-2.25-1.75-3.5-1.75-6c0-2.75 1-4.5 3.5-4.5c1.75 0 2.25 1 3.5 1s1.75-1 3.5-1c2.5 0 3.5 1.75 3.5 4.5c0 2.5-1.25 3.75-1.75 6l-.168 1.008M19.75 14L15 18.25h4l-2.25 3.5");
}

</style>
