<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4c_-mcgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stress-symptom" /></template>
<style>
.r4c_-mcgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 14.25a7.25 7.25 0 1 0 14.5 0a7.25 7.25 0 1 0-14.5 0ZM8.5 12l2 1m5-1l-2 1m-3.75 4.25h4.5M8.5 5.75c-1-.75 1-2 0-3M12 5c-1-.75 1-1.75 0-2.5m3.5 3.25c-1-.75 1-2 0-3");
}

</style>
