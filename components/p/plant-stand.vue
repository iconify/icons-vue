<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm-52yb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-stand" /></template>
<style>
.cm-52yb_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 12.5l-.75-4h7.5l-.75 4m-3-4c-.5-3.5-2.5-5-5.5-5c0 3 2 5 5.5 5Zm0 0C12.5 5 14.5 3 17.5 3c0 3.5-2 5.5-5.5 5.5Zm-5 4h10m-5 0v9m-3.5 0h7");
}

</style>
