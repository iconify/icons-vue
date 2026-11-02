<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q8abciafc"/><path class="x24cvsbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q8abciafc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.315 15.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114");
}

.x24cvsbyw {
  d: path("m2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414L13 16.414V17a1 1 0 0 1-2 0v-2.586L1.293 4.707a.999.999 0 1 1 1.414-1.414m13.74 1.813l2 1a1 1 0 1 1-.894 1.788l-2-1a2.1 2.1 0 0 0-.951-.228C13.828 6.668 13 7.15 13 8a1 1 0 0 1-2 0a3.15 3.15 0 0 1 .536-1.774a3.4 3.4 0 0 1 1.328-1.154c1.127-.564 2.465-.526 3.583.034");
}

</style>
