<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cttop4l8d"/><path class="wl1bpk9ni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-aries-bulk-sharp" /></template>
<style>
.cttop4l8d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.2 5.599A4 4 0 1 0 8 12a1 1 0 0 1 0 2a5.9 5.9 0 0 1-2.336-.472A6 6 0 0 1 3.64 3.879A6 6 0 0 1 12 3.525a6.003 6.003 0 0 1 9.766 6.136A6 6 0 0 1 16 14a1 1 0 0 1 0-2a4 4 0 1 0-3.2-6.4a1 1 0 0 1-1.6 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.wl1bpk9ni {
  d: path("M13 5v16a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

</style>
