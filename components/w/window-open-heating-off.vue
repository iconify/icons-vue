<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc5iqvyyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:window-open-heating-off" /></template>
<style>
.vc5iqvyyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h12v12h-12Zm12.219 11.865l-.219.135v-12l3.25 1.75v8.009M8.5 2.5v12m-6-6h6m10 6.75c1.5 1.25 2.75 2.5 2.75 3.75a2.75 2.75 0 0 1-5.5 0c0-1.25 1.25-2.5 2.75-3.75Zm-2 1.25l5 5");
}

</style>
