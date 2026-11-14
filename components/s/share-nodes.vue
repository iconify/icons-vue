<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teb3e4hqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:share-nodes" /></template>
<style>
.teb3e4hqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12.5 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-7.75-7.75l8-4m-8 6.5l8 4");
}

</style>
