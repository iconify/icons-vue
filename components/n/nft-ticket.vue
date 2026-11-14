<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b1o_cpvkb"/><path class="oaiojeb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nft-ticket" /></template>
<style>
.b1o_cpvkb {
  d: path("M4.5 5.5h15a2 2 0 0 1 2 2v2a2.5 2.5 0 0 0 0 5v2a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-2a2.5 2.5 0 0 0 0-5v-2a2 2 0 0 1 2-2Z");
}

.oaiojeb5b {
  d: path("m12 8.5l3.031 1.75v3.5L12 15.5l-3.031-1.75v-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
