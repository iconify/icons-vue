<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="w1yqn1hbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:movie" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1yqn1hbz {
  d: path("M10.5 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-2 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-6 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-2-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12 12h.01");
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
