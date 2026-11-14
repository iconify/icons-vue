<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3vst_b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:satellite-tracking" /></template>
<style>
.g3vst_b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.702 9.763l1.061-1.061a1.75 1.75 0 0 1 2.474 0l1.061 1.061a1.75 1.75 0 0 1 0 2.474l-1.061 1.061a1.75 1.75 0 0 1-2.474 0l-1.061-1.061a1.75 1.75 0 0 1 0-2.474m5.48-6.188l.354-.353a1.5 1.5 0 0 1 2.121 0l2.121 2.121a1.5 1.5 0 0 1 0 2.121l-.353.354a1.5 1.5 0 0 1-2.122 0l-2.121-2.121a1.5 1.5 0 0 1 0-2.122M3.222 14.536l.353-.354a1.5 1.5 0 0 1 2.122 0l2.121 2.121a1.5 1.5 0 0 1 0 2.122l-.354.353a1.5 1.5 0 0 1-2.121 0l-2.121-2.121a1.5 1.5 0 0 1 0-2.121m9.546-5.304l2.475-2.475m-8.486 8.486l2.475-2.475M16.25 18.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M18.5 15v7M15 18.5h7");
}

</style>
