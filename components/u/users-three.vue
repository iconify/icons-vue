<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4g64mb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:users-three" /></template>
<style>
.f4g64mb4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 19.5c0-2.8 2.5-4.75 5.5-4.75s5.5 1.95 5.5 4.75c0 .5-.4 1-1 1h-9c-.6 0-1-.5-1-1ZM9 7.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.75 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm14 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM2 17.5c0-1.9 1.2-3.25 3-3.5m17 3.5c0-1.9-1.2-3.25-3-3.5");
}

</style>
