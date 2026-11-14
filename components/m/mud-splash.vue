<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r3zyu660c"/><path class="iye1g_tzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mud-splash" /></template>
<style>
.iye1g_tzs {
  fill: currentColor;
  d: path("M4.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM16 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.r3zyu660c {
  d: path("M2.5 20c3.5 0 4.5-3 4-7L9 16l2-7l2 7l2.5-5l1.5 6c0 2 2 3 4.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
