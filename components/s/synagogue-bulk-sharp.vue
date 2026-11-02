<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t6qet8brr"/><path class="oz9_x_b3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.oz9_x_b3d {
  d: path("M13.732 10h1.732a1.002 1.002 0 0 1 .866 1.5l-.866 1.5l.866 1.5a.998.998 0 0 1-.866 1.5h-1.732l-.866 1.5a1.002 1.002 0 0 1-1.732 0l-.866-1.5H8.536a1.002 1.002 0 0 1-.866-1.5l.866-1.5l-.866-1.5a.998.998 0 0 1 .866-1.5h1.732l.866-1.5a1.002 1.002 0 0 1 1.732 0Zm-2.309 2l-.578 1l.578 1h1.154l.578-1l-.578-1Z");
}

.t6qet8brr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8c0-.379.214-.725.553-.894l8-4a1 1 0 0 1 .894 0l8 4A1 1 0 0 1 21 8v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
