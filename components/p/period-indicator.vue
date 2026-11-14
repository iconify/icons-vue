<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6da7polz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:period-indicator" /></template>
<style>
.r6da7polz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.563 3.137a9 9 0 0 1 7.3 7.3m0 3.126a9 9 0 0 1-7.3 7.3m-3.126 0a9 9 0 0 1-7.3-7.3m0-3.126a9 9 0 0 1 7.3-7.3M12 12h.01");
}

</style>
