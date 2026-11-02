<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p23br_wxj"/><path class="hf7yz9bnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:npm-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hf7yz9bnc {
  d: path("M15 10v11a1 1 0 0 1-2 0V10a1 1 0 0 1 2 0");
}

.p23br_wxj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm4 3v12h7V9h2v9h3V6Z");
}

</style>
