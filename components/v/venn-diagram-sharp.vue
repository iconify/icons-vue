<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6pebcc0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:venn-diagram-sharp" /></template>
<style>
.f6pebcc0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm7 0a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0ZM6.5 8.75a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

</style>
