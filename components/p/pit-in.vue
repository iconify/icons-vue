<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xgp7uacfz"/><path class="fzuvp1brt"/><path class="smi5gzb5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pit-in" /></template>
<style>
.fzuvp1brt {
  d: path("M4.5 2.5h5A3.5 3.5 0 0 1 13 6v10.5");
}

.smi5gzb5e {
  d: path("M10.25 13.75L13 16.5l2.75-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgp7uacfz {
  d: path("M7 10h12v11.5H7Z");
}

</style>
