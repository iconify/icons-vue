<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qog63goez"/><path class="xcdlfkbkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nft-collection" /></template>
<style>
.qog63goez {
  d: path("M2.5 2.5h8v8h-8Zm11 0h8v8h-8Zm-11 11h8v8h-8Zm11 0h8v8h-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcdlfkbkk {
  d: path("m17.5 15.75l.529 1.272l1.373.11l-1.046.896l.32 1.34l-1.176-.718l-1.176.718l.32-1.34l-1.046-.896l1.373-.11Z");
}

</style>
