<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxug03kqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:referee-boxing" /></template>
<style>
.pxug03kqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3.5 21.5c0-4 2-6.5 5-7v6l7-6v6l-7-6m7 0c3 .5 5 3 5 7");
}

</style>
