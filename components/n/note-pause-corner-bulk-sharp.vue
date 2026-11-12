<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nyzdfrksg"/><path class="sob878tac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-pause-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nyzdfrksg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

.sob878tac {
  d: path("M16 21a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Z");
}

</style>
