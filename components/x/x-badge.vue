<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="varpyxb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:x-badge" /></template>
<style>
.varpyxb_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m21.5 12l-2.25 3l-.5 3.75l-3.75.5l-3 2.25l-3-2.25l-3.75-.5l-.5-3.75l-2.25-3l2.25-3l.5-3.75L9 4.75l3-2.25l3 2.25l3.75.5l.5 3.75ZM9 9l6 6m0-6l-6 6");
}

</style>
