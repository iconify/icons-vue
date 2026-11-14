<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3yam57rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:season-ticket" /></template>
<style>
.o3yam57rx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h19v3.5a2.5 2.5 0 0 0 0 5V18h-19v-3.5a2.5 2.5 0 0 0 0-5Zm13 0v12M8 10h4.5M8 14h3");
}

</style>
