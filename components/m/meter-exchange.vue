<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="buqxfhbrs"/><path class="ohmxwbcqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meter-exchange" /></template>
<style>
.buqxfhbrs {
  d: path("M12.2 17.5H2.5v-15H18v9.3");
}

.ohmxwbcqo {
  d: path("M6 12.5a4 4 0 0 1 8 0m-4 0l2.25-2.75m2.75 6.5h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
