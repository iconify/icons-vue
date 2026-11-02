<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m0ob9v8as"/><path class="ccg6pqbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webcam-bulk" /></template>
<style>
.ccg6pqbxo {
  d: path("M8 10a4 4 0 1 1 8 0a4 4 0 0 1-8 0m3 7a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.m0ob9v8as {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.629 6.886a8.002 8.002 0 0 1 14.74 6.228a8.002 8.002 0 0 1-14.74-6.228M12 6a4 4 0 1 0 0 8a4 4 0 0 0 0-8");
}

</style>
