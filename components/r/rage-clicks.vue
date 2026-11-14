<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9pi43ymk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rage-clicks" /></template>
<style>
.v9pi43ymk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 9.5l9.75 4.5L15 15.25L13.75 20Zm0-7V6m-7 3.5H6m-3-6l1.75.5l-.5 1.25L6.5 6.5");
}

</style>
