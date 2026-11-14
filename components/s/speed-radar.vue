<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh7l-mtwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:speed-radar" /></template>
<style>
.gh7l-mtwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5h13v6h-13Zm6 6l1.5 8.5h3.5L18 11M6.25 6a3 3 0 0 0 0 4M4 4a6 6 0 0 0 0 8");
}

</style>
