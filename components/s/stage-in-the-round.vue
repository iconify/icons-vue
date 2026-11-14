<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujkwkwbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stage-in-the-round" /></template>
<style>
.ujkwkwbmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7.078-8.457a9 9 0 0 1 5.379 5.379m0 6.156a9 9 0 0 1-5.379 5.379m-6.156 0a9 9 0 0 1-5.379-5.379m0-6.156a9 9 0 0 1 5.379-5.379");
}

</style>
