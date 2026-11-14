<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z2dujjblb"/><path class="ojwn5sbpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treat-jar" /></template>
<style>
.ojwn5sbpc {
  d: path("M9.75 13.25h4.5a1.25 1.25 0 1 1 2 0q-.75.75 0 1.5a1.25 1.25 0 1 1-2 0h-4.5a1.25 1.25 0 1 1-2 0q.75-.75 0-1.5a1.25 1.25 0 1 1 2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2dujjblb {
  d: path("M3.5 2.75h17v4h-17Zm1 4V18.5A2.5 2.5 0 0 0 7 21h10a2.5 2.5 0 0 0 2.5-2.5V6.75");
}

</style>
