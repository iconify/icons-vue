<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqnx22b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:molecule-search" /></template>
<style>
.vqnx22b6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-4.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm14-7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-8 2L6.25 12M13 6.25h3.5M15.25 17.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
