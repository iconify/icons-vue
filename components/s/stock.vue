<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ss4abvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stock" /></template>
<style>
.o5ss4abvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4v16M17 6v12M6.5 8h1A1.5 1.5 0 0 1 9 9.5v4A1.5 1.5 0 0 1 7.5 15h-1A1.5 1.5 0 0 1 5 13.5v-4A1.5 1.5 0 0 1 6.5 8m10 1.5h1A1.5 1.5 0 0 1 19 11v2a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 15 13v-2a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
