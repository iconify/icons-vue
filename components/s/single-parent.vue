<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9iub0bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:single-parent" /></template>
<style>
.u9iub0bvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM3 21.5v-5.25a4.5 4.5 0 0 1 9 0v5.25M15.75 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1 10.5v-2.75a3 3 0 0 1 6 0v2.75");
}

</style>
