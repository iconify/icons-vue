<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pn2r-9bzq"/><path class="i46k68_po"/><path class="ko6o-6b9b"/><path class="p8jx-kb8x"/><path class="ja8v-rhtc"/><path class="ne6lh4btq"/><path class="zbfkny6yh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reel-2-broken" /></template>
<style>
.i46k68_po {
  d: path("M12 9C13.6569 9 15 10.3431 15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja8v-rhtc {
  stroke-linejoin: round;
  d: path("M18.5 12H18.5001");
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.ne6lh4btq {
  stroke-linejoin: round;
  d: path("M12 18.5H12.0001");
}

.p8jx-kb8x {
  stroke-linejoin: round;
  d: path("M12 5.5H12.0001");
}

.pn2r-9bzq {
  d: path("M12 22L22 22");
}

.zbfkny6yh {
  stroke-linejoin: round;
  d: path("M5.5 12H5.5001");
}

</style>
