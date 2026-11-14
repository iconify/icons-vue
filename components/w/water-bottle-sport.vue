<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="verzvwgjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-bottle-sport" /></template>
<style>
.verzvwgjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.875 8h2.25a4.375 4.375 0 0 1 4.375 4.375v4.75a4.375 4.375 0 0 1-4.375 4.375h-2.25A4.375 4.375 0 0 1 6.5 17.125v-4.75A4.375 4.375 0 0 1 10.875 8m-.75-3.25h3.75A1.625 1.625 0 0 1 15.5 6.375A1.625 1.625 0 0 1 13.875 8h-3.75A1.625 1.625 0 0 1 8.5 6.375a1.625 1.625 0 0 1 1.625-1.625M12 2.5v2.25M6.5 13h11");
}

</style>
