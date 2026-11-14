<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ppnccyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swipe-left" /></template>
<style>
.z6ppnccyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 15.5v-8a1.5 1.5 0 0 1 3 0v5h4.5A2.5 2.5 0 0 1 18 15v1.5c0 2.75-2 4.5-4.75 4.5h-.75c-2 0-3.25-.75-4.25-2L5.5 15.75A1.75 1.75 0 0 1 8 15.5m6-10h7M16.5 3L14 5.5L16.5 8");
}

</style>
