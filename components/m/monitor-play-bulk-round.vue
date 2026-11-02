<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r889qqats"/><path class="xtuit9bbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r889qqats {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v5a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5Z");
}

.xtuit9bbs {
  d: path("M9 7a.998.998 0 0 1 1.6-.8l4 3a1 1 0 0 1 0 1.6l-4 3A.999.999 0 0 1 9 13Zm2 4l1.333-1L11 9Zm-2 8h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
