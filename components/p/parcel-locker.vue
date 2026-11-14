<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bpcae8bqt"/><path class="e0o0xpbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parcel-locker" /></template>
<style>
.bpcae8bqt {
  d: path("M3 2.5h12v19H3Zm12 0L20.75 5v14L15 21.5Z");
}

.e0o0xpbzt {
  d: path("M5.5 11.5h7V18h-7Zm0 2.25h7M9 11.5v2.25M19 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
