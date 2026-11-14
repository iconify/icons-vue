<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mtioimb9g"/><path class="h-aq3qbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:monorepo" /></template>
<style>
.h-aq3qbje {
  d: path("M7.5 8.75h3v3h-3Zm6 0h3v3h-3Zm-6 5.75h3v3h-3Zm6 0h3v3h-3Z");
}

.mtioimb9g {
  d: path("M2.5 6a2 2 0 0 1 2-2H9l2 2h8.5a2 2 0 0 1 2 2v10.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
