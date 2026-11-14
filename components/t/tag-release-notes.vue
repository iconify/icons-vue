<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4w5wyb7k"/><path class="izh96eojh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tag-release-notes" /></template>
<style>
.izh96eojh {
  d: path("M7.25 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5.25-2.5H18m-5.5 5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4w5wyb7k {
  d: path("m3 12l5.5-7H19a2.5 2.5 0 0 1 2.5 2.5v9A2.5 2.5 0 0 1 19 19H8.5Z");
}

</style>
