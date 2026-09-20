<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kt4kzrb6r"/><path class="nvn647bwx"/><path class="p7tekpb9x"/><path class="tea8p3bbk"/><path class="ennto9b9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunlight-break-outline-regular" /></template>
<style>
.ennto9b9x {
  d: path("M16 16h5");
}

.kt4kzrb6r {
  d: path("M5 21V4h8v17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvn647bwx {
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.p7tekpb9x {
  d: path("M16 8h5");
}

.tea8p3bbk {
  d: path("M16 12h5");
}

</style>
