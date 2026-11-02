<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q_ntab3ct"/><path class="gzq1g682w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-minus-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gzq1g682w {
  d: path("M10 13h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

.q_ntab3ct {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m14.591 4.488l7 12A2.999 2.999 0 0 1 19 21H5a2.999 2.999 0 0 1-2.591-4.512l7-12a3 3 0 0 1 5.182 0");
}

</style>
