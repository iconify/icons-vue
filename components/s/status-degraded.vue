<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xtk2aomey"/><path class="c0zbdnbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:status-degraded" /></template>
<style>
.c0zbdnbxb {
  d: path("M13.25 7.5h3v13h-3Zm5.25-4h3v17h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtk2aomey {
  fill: currentColor;
  d: path("M2.75 15h3v5.5h-3ZM8 11.5h3v9H8Z");
}

</style>
