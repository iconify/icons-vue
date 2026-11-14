<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wil0lgkfg"/><path class="ncewmdnjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-mobile-handheld" /></template>
<style>
.ncewmdnjw {
  d: path("M8.25 7.25h7.5v5.5h-7.5ZM9 15.5h.01m2.99 0h.01m2.99 0h.01M9 18.5h.01m2.99 0h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wil0lgkfg {
  d: path("M5.5 4.5h13v17h-13Zm4 0v-1a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v1");
}

</style>
