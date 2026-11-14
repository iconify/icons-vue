<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0x3y8blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scene-night" /></template>
<style>
.c0x3y8blp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 18a7.75 7.75 0 1 1-8-13a6 6 0 0 0 8 13ZM18 3.25l1.061 1.689L20.75 6l-1.689 1.061L18 8.75l-1.061-1.689L15.25 6l1.689-1.061Z");
}

</style>
