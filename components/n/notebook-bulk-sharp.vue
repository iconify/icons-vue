<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m_ax_bbup"/><path class="ka7qkbcrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notebook-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ka7qkbcrn {
  d: path("M9 20a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0Zm3-13h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m0 4h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

.m_ax_bbup {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>
