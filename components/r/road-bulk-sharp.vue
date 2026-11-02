<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ki5efeb2l"/><path class="qxssknb4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:road-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ki5efeb2l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 9a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm0 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm0 6a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

.qxssknb4n {
  d: path("M8.051 2.684a1.001 1.001 0 0 1 1.898.632l-6 18a1.001 1.001 0 0 1-1.898-.632Zm6 .632a1.001 1.001 0 0 1 1.898-.632l6 18a1.001 1.001 0 0 1-1.898.632Z");
}

</style>
