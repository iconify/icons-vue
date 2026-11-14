<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orbm3ccau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rent-vs-buy" /></template>
<style>
.orbm3ccau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 19.5l16-16m-6.5 13l4-4l4 4v5h-8ZM3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h5m-1.5 0v2M12 5v2");
}

</style>
