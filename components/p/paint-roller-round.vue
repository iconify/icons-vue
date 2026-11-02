<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-uunxc6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-roller-round" /></template>
<style>
.u-uunxc6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m14 0h1a3 3 0 0 1 0 6h-3a3 3 0 0 0-3 3m-2 2a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0Z");
}

</style>
