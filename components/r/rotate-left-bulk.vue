<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d-14imbam"/><path class="fbt7w6bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d-14imbam {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 8a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Z");
}

.fbt7w6bcq {
  d: path("M15.707 3.707L14.414 5H17a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V8a1 1 0 0 0-1-1h-2.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414M20 14v4a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2H7a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1v-4a1 1 0 0 1 2 0");
}

</style>
