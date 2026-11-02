<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cy2_i8b5f"/><path class="j6kddzykf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cy2_i8b5f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0m12-1a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Zm-6 8a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.j6kddzykf {
  d: path("m8.293 5.293l2.999-3a1 1 0 0 1 1.415 0l3 3a.999.999 0 1 1-1.414 1.414L13 5.414v8.172l2-2V11a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-1.677-.909l-2.148 2.148a3 3 0 1 1-2.35 0l-2.431-2.43a3 3 0 1 1 .573-2.256L11 13.586V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414M5 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m12 1h2v-2h-2Zm-5.707 5.293a.999.999 0 1 0 1.414 1.414a.999.999 0 1 0-1.414-1.414");
}

</style>
