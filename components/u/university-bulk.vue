<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="edl3hzbmh"/><path class="zr4xd_bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:university-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.edl3hzbmh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m20.351 6.936l-8 3a1 1 0 0 1-.702 0l-8-3a1 1 0 0 1 0-1.872l8-3a1 1 0 0 1 .702 0l8 3a1 1 0 0 1 0 1.872");
}

.zr4xd_bgf {
  d: path("M21 9a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0ZM7 12v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0m4 0v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0M3 22a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2Z");
}

</style>
