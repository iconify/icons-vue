<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="julr6x6-w"/><path class="kf3781y5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-star-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.julr6x6-w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 20a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7c0-.265.105-.52.293-.707l4-4A1 1 0 0 1 9 2h6c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7Zm-8-9.1l-1.2 2.4l-2.8.4l2 2l-.4 2.4l2.4-1.2l2.4 1.2l-.4-2.4l2-2l-2.8-.4Z");
}

.kf3781y5d {
  d: path("M11 5h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2m2.86 7.384l2.281.326a1.001 1.001 0 0 1 .566 1.697l-1.636 1.636l.315 1.893a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L12 18.018l-1.953.976a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.315-1.893l-1.636-1.636a1.001 1.001 0 0 1 .566-1.697l2.281-.326l.966-1.931a.998.998 0 0 1 1.788 0Z");
}

</style>
