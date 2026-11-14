<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n8b3gfbxd"/><path class="k7l6nd_uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:railway-signal-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7l6nd_uq {
  d: path("M6.75 13.75h3a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-3a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5M17.5 6l4-2.5");
}

.n8b3gfbxd {
  d: path("M2.5 19.25v-7.397a1.75 1.75 0 0 1 .671-1.378l4-3.131a1.75 1.75 0 0 1 2.158 0l4 3.131A1.75 1.75 0 0 1 14 11.853v7.397A1.75 1.75 0 0 1 12.25 21h-8a1.75 1.75 0 0 1-1.75-1.75m15 1.75V3.5");
}

</style>
