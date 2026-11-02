<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dc1v17bne"/><path class="fukaebtaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:submarine-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dc1v17bne {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 21a4 4 0 0 1-4-4v-2a4.006 4.006 0 0 1 3-3.874V9a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2h2a5 5 0 0 1 0 10Z");
}

.fukaebtaw {
  d: path("M13.999 3h2a1 1 0 0 1 0 2h-2a1 1 0 0 0-1 .998V8a1 1 0 0 1-2 0V6a3.004 3.004 0 0 1 2.999-3M2 20v-8a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0m10-5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

</style>
