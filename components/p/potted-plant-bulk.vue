<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rilxbd04k"/><path class="fo8wb1bxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:potted-plant-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fo8wb1bxf {
  d: path("M15 13h-2v3a1 1 0 0 1-2 0v-4H9a7 7 0 0 1-7-7V3a1 1 0 0 1 1-1h3a7.01 7.01 0 0 1 6.57 4.58A6.98 6.98 0 0 1 18 4h3a1 1 0 0 1 1 1v1a7 7 0 0 1-7 7M6 4H4v1a5 5 0 0 0 5 5h2V9a5 5 0 0 0-5-5m7 7h2a5 5 0 0 0 5-5h-2a5 5 0 0 0-5 5");
}

.rilxbd04k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 4h3a1 1 0 0 1 1 1v1a7 7 0 0 1-7 7h-3a1 1 0 0 1-1-1H9a7 7 0 0 1-7-7V3a1 1 0 0 1 1-1h3a7.01 7.01 0 0 1 6.57 4.58A6.98 6.98 0 0 1 18 4m-1 11a1 1 0 0 1 1 1v3a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-3a1 1 0 0 1 1-1Z");
}

</style>
