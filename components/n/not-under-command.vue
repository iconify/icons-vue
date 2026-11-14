<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3s1hkhna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:not-under-command" /></template>
<style>
.h3s1hkhna {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm0 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
