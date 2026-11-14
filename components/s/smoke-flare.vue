<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx-0nlcvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smoke-flare" /></template>
<style>
.hx-0nlcvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.712 11.934l.354.354a1.75 1.75 0 0 1 0 2.475l-5.303 5.303a1.75 1.75 0 0 1-2.475 0l-.354-.354a1.75 1.75 0 0 1 0-2.475l5.303-5.303a1.75 1.75 0 0 1 2.475 0m-3.462.816l3 3m2-6.5C12 7 15.5 5.5 14.5 2.5m2 8.75c1-2.25 4-1.25 5-4.75");
}

</style>
