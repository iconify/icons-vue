<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8q5j-b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ward-clerk" /></template>
<style>
.k8q5j-b4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.718 0 1.407.064 2.057.186M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10.25 7.25h3A1.75 1.75 0 0 1 21.5 16v4a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 15 20v-4a1.75 1.75 0 0 1 1.75-1.75m.5 0v7.5m-1.25-5h2.5m-2.5 2.5h2.5");
}

</style>
