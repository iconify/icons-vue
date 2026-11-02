<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="heu1y0tmm"/><path class="fn488883v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fn488883v {
  d: path("m10.293 8.293l3-3a2.414 2.414 0 0 1 3.414 0l3 3a2.414 2.414 0 0 1 0 3.414L18.414 13H19a3 3 0 0 1 3 3v3a3 3 0 0 1-3 3H7a1 1 0 0 1 0-2h1.586l9.707-9.707a.414.414 0 0 0 0-.586l-3-3a.414.414 0 0 0-.586 0l-3 3a.999.999 0 1 1-1.414-1.414M11.414 20H19a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1h-2.586ZM7 16h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

.heu1y0tmm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v12a5 5 0 0 1-10 0Z");
}

</style>
