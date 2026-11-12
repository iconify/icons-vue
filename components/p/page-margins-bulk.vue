<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nvbxjrmac"/><path class="v_vsdqbmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:page-margins-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nvbxjrmac {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2h10a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m3 14h4V8h-4Z");
}

.v_vsdqbmf {
  d: path("M10 6h4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m0 10h4V8h-4Z");
}

</style>
