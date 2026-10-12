<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r13825ieb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plant" /></template>
<style>
.r13825ieb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 13.25h12.5l-1.4 6.6a1.75 1.75 0 0 1-1.7 1.4h-6.3a1.75 1.75 0 0 1-1.7-1.4Zm6.25 0v-4.5m-.75 1.5q-5.625 0-6-5.25q5.625 0 6 5.25m1.5-1.5c.25-3.5 2.25-5.5 6-5.5c-.25 3.5-2.25 5.5-6 5.5");
}

</style>
