<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt4atwbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shoe-fitting-bench" /></template>
<style>
.vt4atwbso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5h19V18h-19ZM5 18v3.5M19 18v3.5m-15-6v-10h4c1 2.5 3 3.5 5.5 4l5 1c1.5.25 2.5 1.5 2.5 3v2M4 12.75h17M9.5 7.5l-1 1.75m3.75-.5l-.75 1.5");
}

</style>
