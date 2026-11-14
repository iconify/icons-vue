<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h-rxsdbeq"/><path class="vg8r6tbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-sticker" /></template>
<style>
.h-rxsdbeq {
  d: path("M21.5 12A9.5 9.5 0 1 1 12 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vg8r6tbjz {
  d: path("M12 2.5c-.25 5.5 3.75 9.75 9.5 9.5M12 2.5l9.5 9.5M7 12h4m-4 3.5h6");
}

</style>
