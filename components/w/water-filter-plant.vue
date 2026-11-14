<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2ev04bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-filter-plant" /></template>
<style>
.j2ev04bpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18V5l-6.5 6v2.5h-5V11L3 5ZM6.5 8h11M12 16.5s-2.5 2-2.5 3a2.5 2.5 0 0 0 5 0c0-1-2.5-3-2.5-3Z");
}

</style>
