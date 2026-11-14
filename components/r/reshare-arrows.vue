<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkc691-kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reshare-arrows" /></template>
<style>
.vkc691-kz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12.5V9a2 2 0 0 1 2-2h15M18 4.5L20.5 7L18 9.5m2.5 2V15a2 2 0 0 1-2 2h-15M6 14.5L3.5 17L6 19.5");
}

</style>
