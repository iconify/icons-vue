<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3a0_5brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sequence-diagram" /></template>
<style>
.h3a0_5brx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h6V7h-6Zm13 0h6V7h-6ZM5.5 7v14.5M18.5 7v14.5m-13-9h13m-2.75-2.75l2.75 2.75l-2.75 2.75m2.75 3.25h-13m2.75-2.75L5.5 18.5l2.75 2.75");
}

</style>
