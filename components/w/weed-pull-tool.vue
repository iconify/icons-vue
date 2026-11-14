<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7qi1eb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weed-pull-tool" /></template>
<style>
.g7qi1eb4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.288 19.737l4.949-4.949l2.475 2.475l-4.949 4.949ZM9.5 16l5.5-5.5M17.5 6L15 10.5L19.5 8m-13-1.5v5m0-5c0-2.5-1.75-4-4-4c0 2.5 1.75 4 4 4Zm0 0c0-2.5 1.75-4 4-4c0 2.5-1.75 4-4 4Z");
}

</style>
