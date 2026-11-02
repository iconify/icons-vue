<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="erm1a-b0c"/><path class="oz9_x_b3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.erm1a-b0c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 22a5 5 0 0 1-5-5v-7c0-1.693 1.069-3.152 2.553-3.894l4-2a5.47 5.47 0 0 1 4.894 0l4 2C19.931 6.848 21 8.307 21 10v7a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22Z");
}

.oz9_x_b3d {
  d: path("M13.732 10h1.732a1.002 1.002 0 0 1 .866 1.5l-.866 1.5l.866 1.5a.998.998 0 0 1-.866 1.5h-1.732l-.866 1.5a1.002 1.002 0 0 1-1.732 0l-.866-1.5H8.536a1.002 1.002 0 0 1-.866-1.5l.866-1.5l-.866-1.5a.998.998 0 0 1 .866-1.5h1.732l.866-1.5a1.002 1.002 0 0 1 1.732 0Zm-2.309 2l-.578 1l.578 1h1.154l.578-1l-.578-1Z");
}

</style>
