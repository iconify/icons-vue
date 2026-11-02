<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="epmqilkpp"/><path class="ptlk4caci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-right-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.epmqilkpp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 10v6a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4v-6a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4");
}

.ptlk4caci {
  d: path("m9.707 2.293l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L9.586 7H9a3 3 0 0 0-3 3a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 9 5h.586L8.293 3.707a.999.999 0 1 1 1.414-1.414M6 14v2a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V9a2 2 0 0 0-2-2a1 1 0 0 1 0-2c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 20 9v7a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 21H9a5 5 0 0 1-5-5v-2a1 1 0 0 1 2 0");
}

</style>
