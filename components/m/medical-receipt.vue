<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f0g_-9l1t"/><path class="x4bg8r2ga"/><path class="okltl_ixs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medical-receipt" /></template>
<style>
.f0g_-9l1t {
  d: path("M5.5 2.5h13v19L16.75 20L15 21.5L13.25 20l-1.75 1.5L9.75 20L8 21.5L6.25 20l-.75.75Z");
}

.okltl_ixs {
  d: path("M8.5 13h7m-7 2.75h7M8.5 18H12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x4bg8r2ga {
  fill: currentColor;
  d: path("M10.75 4.25h2.5v1.5h1.5v2.5h-1.5v1.5h-2.5v-1.5h-1.5v-2.5h1.5Z");
}

</style>
