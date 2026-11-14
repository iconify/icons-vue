<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wtr643ljb"/><path class="pbb_6x6bz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pharmacist" /></template>
<style>
.pbb_6x6bz {
  d: path("M8.75 14.5L11 18l1.211-1.884M16.25 14h4.5v2.5h-4.5ZM15 16.5h6.5V22H15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wtr643ljb {
  d: path("M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-3.5 14v-2c0-3 3.5-5.25 7.5-5.25q.621 0 1.222.071");
}

</style>
