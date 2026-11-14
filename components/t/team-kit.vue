<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-_zcobjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:team-kit" /></template>
<style>
.s-_zcobjz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3L3 6l1.75 4.5L7 9.5V21h10V9.5l2.25 1L21 6l-5-3c-.5 2-2 3-4 3S8.5 5 8 3ZM7 13h10");
}

</style>
