<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yj5pembjq"/><path class="c4awqybhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-bulk" /></template>
<style>
.c4awqybhy {
  d: path("M10 8h4a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2m4 4v-2h-4v2Zm-4 2v2h4v-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.yj5pembjq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 19V5a3 3 0 0 1 3-3h7c1.039 0 1.992.578 2.707 1.293l2 2C19.422 6.008 20 6.961 20 8v11a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3m11 1a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3Z");
}

</style>
