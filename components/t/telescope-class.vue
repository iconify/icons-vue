<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkdgyac6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:telescope-class" /></template>
<style>
.vkdgyac6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.811 9.646l11.782-5.494l1.69 3.625l-11.782 5.494ZM12 11.5L8 20m4-8.5l4 8.5m-4-8.5V20");
}

</style>
