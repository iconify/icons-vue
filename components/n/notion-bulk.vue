<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jg241y8ky"/><path class="wqadq9twz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notion-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jg241y8ky {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2 3.414l3.293 3.293a.999.999 0 1 0 1.414-1.414L3.414 2H18c.265 0 .52.105.707.293l3 3A1 1 0 0 1 22 6v15a1 1 0 0 1-1 1H6a1 1 0 0 1-.707-.293l-3-3A1 1 0 0 1 2 18ZM19 7H8a1 1 0 0 0-1 1v11a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1");
}

.wqadq9twz {
  d: path("M10 10a.999.999 0 0 1 1.814-.581L15 13.88V10a1 1 0 0 1 2 0v7a.999.999 0 0 1-1.814.581L12 13.12V17a1 1 0 0 1-2 0Z");
}

</style>
