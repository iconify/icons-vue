<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rkjj_36uj"/><path class="h1gvwe7dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:trend-up-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h1gvwe7dz {
  d: path("M232 48h-64a8 8 0 0 0-5.66 13.66L188.69 88L136 140.69l-34.34-34.35a8 8 0 0 0-11.32 0l-72 72a8 8 0 0 0 11.32 11.32L96 123.31l34.34 34.35a8 8 0 0 0 11.32 0L200 99.31l26.34 26.35A8 8 0 0 0 240 120V56a8 8 0 0 0-8-8m-8 52.69L187.31 64H224Z");
}

.rkjj_36uj {
  d: path("M232 56v64l-64-64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
