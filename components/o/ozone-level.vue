<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8gpctbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ozone-level" /></template>
<style>
.i8gpctbgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm12 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM7.25 17a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm1-10.5h6.5M6.5 9L9 14.5m7-5.75l-4.5 6m4 6.25v-2.5m2.75 2.5v-4.5M21 21v-6.5");
}

</style>
