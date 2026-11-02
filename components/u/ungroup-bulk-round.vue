<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zp76l5bgd"/><path class="b5_jfabhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ungroup-bulk-round" /></template>
<style>
.b5_jfabhs {
  d: path("M17 13a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-3a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3Zm-3 2a.997.997 0 0 0-1 1v1a1 1 0 0 0 1 1h3a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zp76l5bgd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 4h3a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3");
}

</style>
