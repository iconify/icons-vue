<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y34jr0bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-x-report" /></template>
<style>
.y34jr0bdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.186 20.535L8.5 19L5 21V3h14v8.2m-6.599 9.571L12 21l-.38-.217M8.5 7.5h7m-7 3.5h7m-7 3.5h3M16 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-4v.5m0 7v.5m-4-4h.5m7 0h.5");
}

</style>
