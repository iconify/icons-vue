<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gem-s1b1d"/><path class="ovcd9bbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-color-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gem-s1b1d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 19h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

.ovcd9bbkm {
  d: path("M11.051 3.684a1 1 0 0 1 1.898 0l4 12a1.001 1.001 0 0 1-1.898.632L13.946 13h-3.892l-1.105 3.316a1.001 1.001 0 0 1-1.898-.632ZM13.279 11L12 7.162L10.721 11Z");
}

</style>
