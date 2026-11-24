<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n_smkee7f"/><path class="augsv1bju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:windmill-bulk-sharp" /></template>
<style>
.augsv1bju {
  d: path("M11.293 8.707a1 1 0 1 0 1.414-1.414a1 1 0 0 0-1.414 1.414m-2.001-2l-2.999-3a.999.999 0 1 1 1.414-1.414l3 2.999a3.02 3.02 0 0 1 2.586 0l3-2.999a.999.999 0 1 1 1.414 1.414l-2.999 3a3.02 3.02 0 0 1 0 2.586l2.999 3a.999.999 0 1 1-1.414 1.414l-3-2.999a3.02 3.02 0 0 1-2.586 0l-3 2.999a.999.999 0 1 1-1.414-1.414l2.999-3a3.02 3.02 0 0 1 0-2.586M21 22H3a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.n_smkee7f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 8a3 3 0 1 1 6 0a3 3 0 0 1-6 0m3.447 6.106l4 2c.261.13.452.368.523.651l1 4A.998.998 0 0 1 17 22H7a.998.998 0 0 1-.97-1.243l1-4a1 1 0 0 1 .523-.651l4-2a1 1 0 0 1 .894 0");
}

</style>
