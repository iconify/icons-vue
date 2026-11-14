<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1pz4cc2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:take-out-trash" /></template>
<style>
.r1pz4cc2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 6.5l1 13A1.5 1.5 0 0 0 6.5 21h3a1.5 1.5 0 0 0 1.5-1.5l1-13m-9.5 0h11M6.5 4h3M14 14h7m-2.5-2.5L21 14l-2.5 2.5");
}

</style>
