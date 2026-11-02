<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vvdc0tbda"/><path class="hyyoeff1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spell-check-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hyyoeff1b {
  d: path("M14 5.535a4 4 0 1 1-.089 6.877A1 1 0 0 1 12 12V4a1 1 0 0 1 2 0ZM14 9a2 2 0 1 0 3.999.001A2 2 0 0 0 14 9M8.089 5.588A1 1 0 0 1 10 6v6a1 1 0 0 1-1.911.412a4.002 4.002 0 0 1-5.132-6.009a4 4 0 0 1 5.132-.815M8 9a2 2 0 1 0-3.999-.001A2 2 0 0 0 8 9");
}

.vvdc0tbda {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15 18.586l5.293-5.293a.999.999 0 1 1 1.414 1.414l-6 6a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414Z");
}

</style>
