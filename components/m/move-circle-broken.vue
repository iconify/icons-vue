<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c4v1z3pvf"/><path class="dfvtxfbxr"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-circle-broken" /></template>
<style>
.c4v1z3pvf {
  stroke-linejoin: round;
  d: path("M16.9497 14.1213L19.0711 12L16.9497 9.8787M19.0711 12H14.1213M7.05025 9.8787L4.92893 12L7.05025 14.1213M4.92893 12H9.87868");
}

.dfvtxfbxr {
  stroke-linejoin: round;
  d: path("M9.8789 7.05025L12.0002 4.92893L14.1215 7.05025M12.0002 4.92893V9.87868M14.1215 16.9497L12.0002 19.0711L9.8789 16.9497M12.0002 19.0711V14.1213");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

</style>
