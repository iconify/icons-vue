<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-gqcdcge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scene" /></template>
<style>
.g-gqcdcge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9a3 3 0 0 0 0 6Zm7.25-1.25a4.25 4.25 0 0 0 0 8.5a7 7 0 0 1 0-8.5M4.25 12h-2M6 8L4.5 6.5M6 16l-1.5 1.5M10 6.25v-2m0 13.5v2");
}

</style>
