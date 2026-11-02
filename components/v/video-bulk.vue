<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s5nt3bc_v"/><path class="lyu_t7bka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lyu_t7bka {
  d: path("M18.553 7.106c.356-.181.75-.274 1.149-.273C20.924 6.836 22 7.735 22 9v6c0 1.265-1.076 2.164-2.298 2.167a2.5 2.5 0 0 1-1.149-.273l-4-2a1 1 0 1 1 .894-1.788l4 2a.6.6 0 0 0 .251.061c.093 0 .302-.044.302-.167V9c0-.123-.209-.167-.302-.167a.6.6 0 0 0-.251.061l-4 2a1 1 0 1 1-.894-1.788Z");
}

.s5nt3bc_v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
