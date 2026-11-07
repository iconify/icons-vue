<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k8nkhzbtz"/><path class="qxp9k-eqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:variable-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k8nkhzbtz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12 10.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L13.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414L12 13.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L10.586 12L8.293 9.707a.999.999 0 1 1 1.414-1.414Z");
}

.qxp9k-eqg {
  d: path("M5.672 8.701a8.43 8.43 0 0 0 0 6.598a9.3 9.3 0 0 0 2.035 2.994a.999.999 0 1 1-1.414 1.414a11.3 11.3 0 0 1-2.465-3.631A10.4 10.4 0 0 1 3 12c-.001-1.4.281-2.787.828-4.076a11.3 11.3 0 0 1 2.465-3.631a.999.999 0 1 1 1.414 1.414a9.3 9.3 0 0 0-2.035 2.994m14.5-.777c.547 1.289.829 2.676.828 4.076c.001 1.4-.281 2.787-.828 4.076a11.3 11.3 0 0 1-2.465 3.631a.999.999 0 1 1-1.414-1.414a9.3 9.3 0 0 0 2.035-2.994a8.42 8.42 0 0 0 0-6.598a9.3 9.3 0 0 0-2.035-2.994a.999.999 0 1 1 1.414-1.414a11.3 11.3 0 0 1 2.465 3.631");
}

</style>
