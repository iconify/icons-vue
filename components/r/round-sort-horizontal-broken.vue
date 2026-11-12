<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_dm05blc"/><path class="aq5i5kwsa"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-sort-horizontal-broken" /></template>
<style>
.aq5i5kwsa {
  stroke-linejoin: round;
  d: path("M8 14.5L16 14.5M13.25 17L16 14.5L13.25 12");
}

.c_dm05blc {
  stroke-linejoin: round;
  d: path("M16 9.5L8 9.5M10.75 12L8 9.5L10.75 7");
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
