<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nk9xv7a7v"/><path class="jgajyzr_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:turtle-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jgajyzr_w {
  d: path("M7.106 11.447L5.581 8.399v-.001a1 1 0 0 1 1.789-.893L8.618 10h2.764l1.248-2.495a1 1 0 1 1 1.789.894l-1.525 3.048a1 1 0 0 1-.88.553H8a1 1 0 0 1-.894-.553");
}

.nk9xv7a7v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 14a8 8 0 0 1 14.247-5H19a3 3 0 1 1 0 6h-1v2a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2v-2H7v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Z");
}

</style>
