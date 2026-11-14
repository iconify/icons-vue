<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmuo7jvht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parachute" /></template>
<style>
.tmuo7jvht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11a9 8.5 0 0 1 18 0q-2.25-1.5-4.5 0q-2.25-1.5-4.5 0q-2.25-1.5-4.5 0Q5.25 9.5 3 11Zm0 0l9 8l9-8m-9 0v8m-1.25 0h2.5v2.5h-2.5Z");
}

</style>
