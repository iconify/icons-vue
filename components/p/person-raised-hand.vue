<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4-2i_txf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-raised-hand" /></template>
<style>
.r4-2i_txf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM10 8v6.5M7 21l3-6.5l3 6.5m-7-9.5l4-3h4.5L16 3");
}

</style>
