<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dhsvhev9z"/><circle class="x6tlt5s8q"/><path class="ykkyycbio"/><path class="n-y7-h-tz"/><path class="muvu13hjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-track-2-broken" /></template>
<style>
.dhsvhev9z {
  d: path("M13 15V11V7");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.muvu13hjo {
  d: path("M14 21.8C13.3538 21.9311 12.6849 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7M21.8 14C21.9311 13.3538 22 12.6849 22 12C22 6.47715 17.5228 2 12 2C10.1786 2 8.47087 2.48697 7 3.33782");
}

.n-y7-h-tz {
  stroke-linejoin: round;
  d: path("M18 22V15M15.5 17.5L18 15L20.5 17.5");
}

.x6tlt5s8q {
  cx: 11px;
  cy: 15px;
  r: 2px;
}

.ykkyycbio {
  d: path("M16 10C14.3431 10 13 8.65685 13 7");
}

</style>
