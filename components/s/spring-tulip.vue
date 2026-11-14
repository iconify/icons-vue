<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kse_6cclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spring-tulip" /></template>
<style>
.kse_6cclz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 4l2.25 2.5l2.25-3l2.25 3L16.5 4v4.5a4.5 4.5 0 0 1-9 0Zm4.5 9v8.5m0-1.5c-4-.5-6-3-6-6c3 .5 5.5 2.5 6 6m0 0c4-.5 6-3 6-6c-3 .5-5.5 2.5-6 6");
}

</style>
