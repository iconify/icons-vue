<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3t8l_52w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:more-horizontal" /></template>
<style>
.u3t8l_52w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM11 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm7.25 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

</style>
