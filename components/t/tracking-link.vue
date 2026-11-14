<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iccqsqbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tracking-link" /></template>
<style>
.iccqsqbpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 14.5l5-5M11 7l1.5-1.5a3.5 3.5 0 0 1 5 5L16 12m-3 5l-1.5 1.5a3.5 3.5 0 0 1-5-5L8 12");
}

</style>
