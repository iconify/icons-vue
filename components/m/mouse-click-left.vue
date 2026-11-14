<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p62uvg4sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mouse-click-left" /></template>
<style>
.p62uvg4sw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 5.5h4A3.5 3.5 0 0 1 20 9v9a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 9 18V9a3.5 3.5 0 0 1 3.5-3.5Zm2 0V11M9 11h11M3 3l2 2M2.5 8.5H5m3.5-6v1");
}

</style>
