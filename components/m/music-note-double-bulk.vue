<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gqjs11iml"/><path class="xhtxj8bhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-double-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gqjs11iml {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 17a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

.xhtxj8bhj {
  d: path("M11 17V6c0-1.265 1.076-2.164 2.298-2.167c.399-.001.793.092 1.149.273l4 2a1 1 0 1 1-.894 1.788l-4-2a.6.6 0 0 0-.251-.061c-.093 0-.302.044-.302.167v2.382l3.447 1.724a1 1 0 1 1-.894 1.788L13 10.618V17a1 1 0 0 1-2 0");
}

</style>
