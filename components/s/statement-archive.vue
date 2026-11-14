<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xt4fnwb6g"/><path class="bfi4ndbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-archive" /></template>
<style>
.bfi4ndbit {
  d: path("M9.5 15h5v2.5h-5Zm0-9.75h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xt4fnwb6g {
  d: path("M2.5 8h19v4.5h-19ZM4 12.5v7a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-7M7 8V3.5a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1V8");
}

</style>
