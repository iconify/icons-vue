<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ww9_l4_vw"/><path class="o-u2efu9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-edit-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o-u2efu9j {
  d: path("M8 12c0-.265.105-.52.293-.707l9-9a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-3 3v.001l-6 5.999A1 1 0 0 1 12 16H9a1 1 0 0 1-1-1Z");
}

.ww9_l4_vw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 3c.265 0 .52.105.707.293l9 9A1 1 0 0 1 21 13v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5Z");
}

</style>
