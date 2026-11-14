<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhtynqbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weed-check" /></template>
<style>
.rhtynqbgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 6a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM10 9.25V21.5m0-2.5l-4.5-1.5L7 16l-3.5-2.25h4L10 16m0-1l3-1.25l-1-1.25l3.5-1.25l-1.5 3L10 17m4.75 1l2 2L21 15.75");
}

</style>
