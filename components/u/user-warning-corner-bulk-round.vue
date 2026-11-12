<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p05d90bur"/><path class="im2m-vbzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-warning-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.im2m-vbzs {
  d: path("M18 18a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0ZM2 21c0-1.862.731-3.636 2.05-4.95a7 7 0 0 1 2.225-1.5A6.9 6.9 0 0 1 9 14a1 1 0 0 1 0 2a4.97 4.97 0 0 0-3.536 1.464A4.97 4.97 0 0 0 4 21a1 1 0 0 1-2 0m15-1h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

.p05d90bur {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m6 8v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

</style>
