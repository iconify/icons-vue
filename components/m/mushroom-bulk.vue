<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ve71b7bqv"/><path class="ehoa_k8uf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mushroom-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ehoa_k8uf {
  d: path("M11 19a1 1 0 0 0 2 0v-8a1 1 0 0 1 2 0v8a3 3 0 1 1-6 0v-8a1 1 0 0 1 2 0Z");
}

.ve71b7bqv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 12h-5v7a3 3 0 1 1-6 0v-7H4a1 1 0 0 1-1-1a9 9 0 0 1 9-9a9 9 0 0 1 9 9a1 1 0 0 1-1 1");
}

</style>
