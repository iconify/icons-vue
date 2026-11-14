<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg39iobum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nanobot" /></template>
<style>
.yg39iobum {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.875 7h4.25a4.375 4.375 0 0 1 4.375 4.375v1.25A4.375 4.375 0 0 1 14.125 17h-4.25A4.375 4.375 0 0 1 5.5 12.625v-1.25A4.375 4.375 0 0 1 9.875 7M12 3v4M8.5 17l-2 4m9-4l2 4M9 12h.01M15 12h.01");
}

</style>
