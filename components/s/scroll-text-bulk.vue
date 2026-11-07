<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b4x2htb7f"/><path class="k7i9sdvjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scroll-text-bulk" /></template>
<style>
.b4x2htb7f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h11a3 3 0 0 1 3 3v11h1a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9H4a2 2 0 0 1-2-2V5a3 3 0 0 1 3-3");
}

.cuyn6tgcc {
  fill: currentColor;
}

.k7i9sdvjr {
  d: path("M8 5v3a1 1 0 0 1-1 1H4a2 2 0 0 1-2-2V5a3 3 0 1 1 6 0M4 5v2h2V5a1 1 0 0 0-2 0m11 2a1 1 0 0 1 0 2h-5a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-5a1 1 0 0 1 0-2Zm-5 7a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3H9a1 1 0 0 1 0-2a1 1 0 0 0 1-1Zm2 0v1c.001.341-.057.679-.171 1H19a1 1 0 0 0 1-1v-1Z");
}

</style>
