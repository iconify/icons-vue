<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpou5lnmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:snowsuit" /></template>
<style>
.kpou5lnmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 7c0-4.25 7-4.25 7 0l4 3l1 5.5h-2.75l-1.25-3v9H13l-1-6l-1 6H7.5v-9l-1.25 3H3.5l1-5.5Zm3.5.5v5");
}

</style>
