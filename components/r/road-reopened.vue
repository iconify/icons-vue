<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1untzb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:road-reopened" /></template>
<style>
.i1untzb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5L3 21.5m11.5-19l4 11.5M12 4v2.5m0 3.5v3m0 3.5v.3m0 2.4v.8m2.75-2l2 2L21 15.75");
}

</style>
