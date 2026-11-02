<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jvxgz6bla"/><path class="ss3d290uf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jvxgz6bla {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 10h3a1 1 0 0 1 0 2h-2v7a1 1 0 0 1-2 0v-7h-2a1 1 0 0 1 0-2Z");
}

.ss3d290uf {
  d: path("M8 4h5a1 1 0 0 1 0 2H9v13a1 1 0 0 1-2 0V6H3a1 1 0 0 1 0-2Z");
}

</style>
