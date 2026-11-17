<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pvtn28bvv"/><path class="hvv4899io"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toilet-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hvv4899io {
  d: path("M4 10h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

.pvtn28bvv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11V6a4 4 0 0 1 8 0v4h9a1 1 0 0 1 1 1a6.9 6.9 0 0 1-.551 2.725a6.9 6.9 0 0 1-1.499 2.225A7 7 0 0 1 15 17.93V19a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3v-1.082A6.01 6.01 0 0 1 3 12Z");
}

</style>
