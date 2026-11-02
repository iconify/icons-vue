<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kgq91yb-d"/><path class="d_8oape8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podium-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d_8oape8w {
  d: path("M12.293 8.293A1 1 0 0 1 14 9v6a1 1 0 0 1-2 0v-3.586l-.293.293a.999.999 0 1 1-1.414-1.414ZM9 12v9a1 1 0 0 1-2 0v-9a1 1 0 0 1 2 0m8 3v6a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0");
}

.kgq91yb-d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 11V7a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v7h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-5a3 3 0 0 1 3-3Z");
}

</style>
