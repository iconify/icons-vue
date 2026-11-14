<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="maw7r-3ly"/><path class="s7zwy_bcc"/><path class="lfwz8z9qo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:timeline-vertical" /></template>
<style>
.lfwz8z9qo {
  d: path("M11 4.25h10v4.5H11Zm0 11h10v4.5H11Z");
}

.maw7r-3ly {
  d: path("M6 2.5v19");
}

.s7zwy_bcc {
  fill: currentColor;
  d: path("M4 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
