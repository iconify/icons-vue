<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4dc3b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:psychiatrist" /></template>
<style>
.qa4dc3b9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 9.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM2.5 21c0-3.5 2-5.5 5-5.5s5 2 5 5.5M15 2.5h5A1.5 1.5 0 0 1 21.5 4v6a1.5 1.5 0 0 1-1.5 1.5h-2.5L15 14v-2.5a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 15 2.5Z");
}

</style>
