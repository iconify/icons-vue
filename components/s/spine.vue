<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mob1xmb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spine" /></template>
<style>
.mob1xmb3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.875 2.5h4.25A1.375 1.375 0 0 1 15.5 3.875a1.375 1.375 0 0 1-1.375 1.375h-4.25A1.375 1.375 0 0 1 8.5 3.875A1.375 1.375 0 0 1 9.875 2.5m0 5.5h4.25A1.375 1.375 0 0 1 15.5 9.375a1.375 1.375 0 0 1-1.375 1.375h-4.25A1.375 1.375 0 0 1 8.5 9.375A1.375 1.375 0 0 1 9.875 8m0 5.5h4.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-4.25A1.375 1.375 0 0 1 8.5 14.875A1.375 1.375 0 0 1 9.875 13.5m0 5.5h4.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-4.25A1.375 1.375 0 0 1 8.5 20.375A1.375 1.375 0 0 1 9.875 19");
}

</style>
