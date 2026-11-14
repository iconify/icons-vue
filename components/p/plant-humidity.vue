<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chqqp8mom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-humidity" /></template>
<style>
.chqqp8mom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10.5a3 3 0 0 1 0-6A8 8 0 0 1 17 5a2.75 2.75 0 0 1 0 5.5ZM5 13.25v3m14-3v3m-7 5.25v-4c-.25-2.25-1.75-3.5-4-3.5c0 2.25 1.75 3.5 4 3.5c.25-2.5 1.75-4 4-4c0 2.5-1.75 4-4 4");
}

</style>
