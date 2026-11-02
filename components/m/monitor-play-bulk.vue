<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x9qbi2awd"/><path class="xtuit9bbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.x9qbi2awd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.xtuit9bbs {
  d: path("M9 7a.998.998 0 0 1 1.6-.8l4 3a1 1 0 0 1 0 1.6l-4 3A.999.999 0 0 1 9 13Zm2 4l1.333-1L11 9Zm-2 8h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
