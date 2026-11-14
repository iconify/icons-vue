<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auy5-ohpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shirt-on-hanger" /></template>
<style>
.auy5-ohpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9L4 11.5L5.5 15l2-1v7h9v-7l2 1l1.5-3.5L15.5 9q-3.5 2.5-7 0Zm1.75-4.5A1.75 1.75 0 1 1 12 6.25v1M8.5 9L12 7.25L15.5 9");
}

</style>
