<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij-mcq8wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:more-vertical" /></template>
<style>
.ij-mcq8wi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM11 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0 7.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
