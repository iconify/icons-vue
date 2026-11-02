<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i186345jk"/><path class="o-u2efu9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-edit-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i186345jk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 3c.265 0 .52.105.707.293l9 9A1 1 0 0 1 21 13v5a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3Z");
}

.o-u2efu9j {
  d: path("M8 12c0-.265.105-.52.293-.707l9-9a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-3 3v.001l-6 5.999A1 1 0 0 1 12 16H9a1 1 0 0 1-1-1Z");
}

</style>
