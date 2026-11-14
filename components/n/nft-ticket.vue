<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xbkl94b0u"/><path class="l7odi8npx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nft-ticket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7odi8npx {
  d: path("m12.75 8.933l1.531.884a1.5 1.5 0 0 1 .75 1.299v1.768a1.5 1.5 0 0 1-.75 1.299l-1.531.884a1.5 1.5 0 0 1-1.5 0l-1.531-.884a1.5 1.5 0 0 1-.75-1.299v-1.768a1.5 1.5 0 0 1 .75-1.299l1.531-.884a1.5 1.5 0 0 1 1.5 0");
}

.xbkl94b0u {
  d: path("M4.5 5.5h15a2 2 0 0 1 2 2v2a2.5 2.5 0 0 0 0 5v2a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-2a2.5 2.5 0 0 0 0-5v-2a2 2 0 0 1 2-2");
}

</style>
