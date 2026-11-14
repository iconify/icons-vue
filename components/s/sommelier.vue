<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e07yfvb0w"/><path class="iejc_vbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sommelier" /></template>
<style>
.e07yfvb0w {
  d: path("M7 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm7.183 15H3c0-4.5 3.25-8 7.5-8c1.728 0 3.291.579 4.537 1.568");
}

.iejc_vbnc {
  d: path("m8 16l2.5 1.25L13 16v2.5l-2.5-1.25L8 18.5Zm11-2.5v2c-1.5.5-2 1.5-2 2.5v3.5h4V18c0-1-.5-2-2-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
