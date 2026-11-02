<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="npe949b6d"/><path class="o-u2efu9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-edit-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.npe949b6d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.707 3.293l9 9A1 1 0 0 1 21 13v7a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h7c.265 0 .52.105.707.293");
}

.o-u2efu9j {
  d: path("M8 12c0-.265.105-.52.293-.707l9-9a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-3 3v.001l-6 5.999A1 1 0 0 1 12 16H9a1 1 0 0 1-1-1Z");
}

</style>
