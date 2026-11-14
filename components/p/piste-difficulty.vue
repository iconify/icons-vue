<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv78r1bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:piste-difficulty" /></template>
<style>
.cv78r1bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11-4h7.5V11H14Zm-2 9l4.5 4.5l-4.5 4.5L7.5 17Z");
}

</style>
