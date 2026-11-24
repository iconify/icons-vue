<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x5rg_r_va"/><path class="a7v-yzbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-bulk" /></template>
<style>
.a7v-yzbcq {
  d: path("m12.894 5.953l.966 1.931l2.281.326a1.001 1.001 0 0 1 .566 1.697l-1.636 1.636l.315 1.893a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L12 13.518l-1.953.976a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.315-1.893l-1.636-1.636a1.001 1.001 0 0 1 .566-1.697l2.281-.326l.966-1.931a.998.998 0 0 1 1.788 0M21 22H3a1 1 0 0 1 0-2h6v-1a3 3 0 1 1 6 0v1h6a1 1 0 0 1 0 2m-8-2v-1a1 1 0 0 0-2 0v1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.x5rg_r_va {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 22H5a1 1 0 0 1-1-1V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1");
}

</style>
