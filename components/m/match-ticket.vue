<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4p70sbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:match-ticket" /></template>
<style>
.d4p70sbhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6h18v3.5a2.5 2.5 0 0 0 0 5V18H3v-3.5a2.5 2.5 0 0 0 0-5Zm12.5 3v6m-7-3h4");
}

</style>
