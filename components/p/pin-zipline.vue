<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj-3z5b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-zipline" /></template>
<style>
.xj-3z5b0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2 3l20 5m-9.25 3a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM10 5v6.5l1 5l5 3.5m-5-3.5l-1.5 5");
}

</style>
