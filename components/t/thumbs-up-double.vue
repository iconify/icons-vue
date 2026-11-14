<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1maa9b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thumbs-up-double" /></template>
<style>
.m1maa9b3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12.5h2.5l2.5-5c.75-1.25 2.75-1 2.75.75v3.25h2.75a1.75 1.75 0 0 1 1.75 2l-.75 6a2 2 0 0 1-2 2H9Zm2.5 0v9m-8.5-4v-9h3.5l2.5-5c.5-1.25 2.5-1 2.75.5");
}

</style>
