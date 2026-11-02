<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ur4to5ccl"/><path class="qrk9s_b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qrk9s_b5s {
  d: path("M11 8h2a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3m3 4v-1a.997.997 0 0 0-1-1h-2a.997.997 0 0 0-1 1v1Zm-4 2v1a.997.997 0 0 0 1 1h2a.997.997 0 0 0 1-1v-1Z");
}

.ur4to5ccl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 17V7a5 5 0 0 1 5-5h4c1.317 0 2.748.335 3.707 1.293l2 2C19.665 6.252 20 7.683 20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5m10 3a4 4 0 0 0 4-4v-6a4 4 0 0 0-4-4h-4a4 4 0 0 0-4 4v6a4 4 0 0 0 4 4Z");
}

</style>
