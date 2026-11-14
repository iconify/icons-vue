<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkia_7b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sponsored-job" /></template>
<style>
.wkia_7b0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14v9H5ZM8 6h8M8 8.75h5m-1 5c1.75 1.5 2.25 3.75 1.75 5.5h-3.5c-.5-1.75 0-4 1.75-5.5ZM10.25 18l-1.5 1.75m5-1.75l1.5 1.75M12 20.5v1");
}

</style>
