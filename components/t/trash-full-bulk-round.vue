<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xglxx3b2i"/><path class="vo2x_wbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vo2x_wbwy {
  d: path("M11 2h2a3.996 3.996 0 0 1 3.874 3H20a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3.126A4 4 0 0 1 11 2m3.733 3A1.99 1.99 0 0 0 13 4h-2a2 2 0 0 0-.276.019h-.001A2.02 2.02 0 0 0 9.267 5ZM11 10v7a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0m4 0v7a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0");
}

.xglxx3b2i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 5a1 1 0 0 1 1 1v11a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 22h-4a5 5 0 0 1-5-5V6a1 1 0 0 1 1-1Zm-9 5v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0m4 0v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0");
}

</style>
