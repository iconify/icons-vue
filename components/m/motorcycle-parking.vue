<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wncp_wlif"/><path class="qi_bzlg7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:motorcycle-parking" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qi_bzlg7l {
  d: path("M5.75 10L10 7h2l1-2h2m1.25 5l-1.5-6h2.5M17 21.5V16h2a2 2 0 0 1 0 4h-2");
}

.wncp_wlif {
  d: path("M2.5 10A3.25 3.25 0 1 0 9 10a3.25 3.25 0 1 0-6.5 0M13 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
