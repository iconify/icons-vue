<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yv1xdztxx"/><path class="rzz27iuhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rzz27iuhk {
  d: path("M7.158 8.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

.yv1xdztxx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3c.265 0 .52.105.707.293l8 8a1 1 0 0 1 0 1.414l-8 8a1 1 0 0 1-1.414 0l-8-8A1 1 0 0 1 3 12V4a1 1 0 0 1 1-1Z");
}

</style>
