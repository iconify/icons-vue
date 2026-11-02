<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bx773o40v"/><path class="oz9_x_b3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-bulk" /></template>
<style>
.bx773o40v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 22H6a3 3 0 0 1-3-3V9c.001-1.348 1.478-2.357 2.553-2.894l6-3a1 1 0 0 1 .894 0l6 3C19.522 6.643 20.999 7.652 21 9v10a3 3 0 0 1-3 3");
}

.cuyn6tgcc {
  fill: currentColor;
}

.oz9_x_b3d {
  d: path("M13.732 10h1.732a1.002 1.002 0 0 1 .866 1.5l-.866 1.5l.866 1.5a.998.998 0 0 1-.866 1.5h-1.732l-.866 1.5a1.002 1.002 0 0 1-1.732 0l-.866-1.5H8.536a1.002 1.002 0 0 1-.866-1.5l.866-1.5l-.866-1.5a.998.998 0 0 1 .866-1.5h1.732l.866-1.5a1.002 1.002 0 0 1 1.732 0Zm-2.309 2l-.578 1l.578 1h1.154l.578-1l-.578-1Z");
}

</style>
