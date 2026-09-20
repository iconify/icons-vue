<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="xmm7cscja"/><path class="ivf5ys14p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rss-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ivf5ys14p {
  d: path("M224 192a8 8 0 0 1-16 0c0-79.4-64.6-144-144-144a8 8 0 0 1 0-16c88.22 0 160 71.78 160 160M64 104a8 8 0 0 0 0 16a72.08 72.08 0 0 1 72 72a8 8 0 0 0 16 0a88.1 88.1 0 0 0-88-88m4 72a12 12 0 1 0 12 12a12 12 0 0 0-12-12");
}

.xmm7cscja {
  d: path("M216 192H64V40a152 152 0 0 1 152 152");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
