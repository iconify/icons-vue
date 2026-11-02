<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ggx0oswmo"/><path class="hbcb0m4cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:repeat-one-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ggx0oswmo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h18v12H3Z");
}

.hbcb0m4cg {
  d: path("M17.293 8.293L18.586 7H4v4a1 1 0 0 1-2 0V6a1 1 0 0 1 1-1h15.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414m-8 2l2-2A1 1 0 0 1 13 9v6a1 1 0 0 1-2 0v-3.586l-.293.293a.999.999 0 1 1-1.414-1.414M22 13v5a1 1 0 0 1-1 1H5.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L5.414 17H20v-4a1 1 0 0 1 2 0");
}

</style>
