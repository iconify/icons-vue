<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7n2k8wdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-tag-edit" /></template>
<style>
.s7n2k8wdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 19.5H8.5l-5-7.5l5-7.5h11v5.8M8.25 12h.01m5.99 9.75l.25-2.5L19.75 14L22 16.25l-5.25 5.25Zm3.5-5.75L20 18.25");
}

</style>
