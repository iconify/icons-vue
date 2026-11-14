<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnjgo374d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:org-node" /></template>
<style>
.jnjgo374d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5h7v5h-7Zm3.5 5V11m-6.5 4v-2.5A1.5 1.5 0 0 1 7 11h10a1.5 1.5 0 0 1 1.5 1.5V15m-16 0h6v5.5h-6Zm13 0h6v5.5h-6Z");
}

</style>
