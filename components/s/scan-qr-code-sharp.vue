<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vwu5wvbuq"/><path class="gowt8l0oy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-qr-code-sharp" /></template>
<style>
.gowt8l0oy {
  fill: currentColor;
  d: path("M11 2L13 2L13 4L11 4L11 2ZM20 11L22 11L22 13L20 13L20 11ZM15.5 6.5L17.5 6.5L17.5 8.5L15.5 8.5L15.5 6.5Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vwu5wvbuq {
  d: path("M3 9L3 3L9 3M15 3L21 3L21 9M21 15L21 21L15 21M9 21L3 21L3 15M12 6L12 12L18 12M12 22L12 16L6 16M9 12L2 12M7.5 6L7.5 9M16.5 15L16.5 18");
}

</style>
