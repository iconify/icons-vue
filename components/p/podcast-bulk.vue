<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rg9ttz14n"/><path class="ezg_nb0vk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podcast-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ezg_nb0vk {
  d: path("M13 13.733V21a1 1 0 0 1-2 0v-7.267a2.001 2.001 0 1 1 2 0");
}

.rg9ttz14n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.786 8.107A10.003 10.003 0 0 1 22 12a1 1 0 0 1-2 0a8 8 0 0 0-16 0a1 1 0 0 1-2 0a9.9 9.9 0 0 1 .786-3.893m3.522 5.79A6 6 0 1 1 16.8 15.6a1 1 0 0 1-1.6-1.2a4 4 0 1 0-6.4 0a1 1 0 0 1-1.6 1.2a6 6 0 0 1-.892-1.703");
}

</style>
