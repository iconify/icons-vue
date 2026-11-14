<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2-ol8q3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signalised-roundabout" /></template>
<style>
.h2-ol8q3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8.25a5.5 5.5 0 0 1 3.75 6.25m1.5-1.25l-1.5 1.25l-1.25-1.5m-.75 4.75a5.5 5.5 0 0 1-7 0m.25 2l-.25-2l1.75-.25m-3.75-3a5.5 5.5 0 0 1 3.75-6.25m-2-.75l2 .75L5.5 10m12-7.5h4v11h-4Zm2 3h.01m-.01 2.75h.01M19.5 11h.01m-.01 2.5v8");
}

</style>
