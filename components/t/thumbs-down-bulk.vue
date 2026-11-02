<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rekmyq-eg"/><path class="zvpr52bet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rekmyq-eg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 15a3 3 0 0 1-3-3V5a3.001 3.001 0 0 1 5-2.236A3 3 0 0 1 9 2h8c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l2 6A1 1 0 0 1 22 10v2a3 3 0 0 1-3 3h-2a.997.997 0 0 0-1 1v3a3 3 0 1 1-6 0v-1a3 3 0 0 0-3-3Z");
}

.zvpr52bet {
  d: path("M2 12V5a3 3 0 1 1 6 0v9a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3m4 1V5a1 1 0 0 0-2 0v7a.997.997 0 0 0 1 1Z");
}

</style>
