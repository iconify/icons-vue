<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xejcjvbba"/><path class="nwq_z96xf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-right-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nwq_z96xf {
  d: path("m9.707 2.293l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L9.586 7H7a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0V8a3 3 0 0 1 3-3h2.586L8.293 3.707a.999.999 0 1 1 1.414-1.414M6 14v4a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-4a1 1 0 0 1 2 0");
}

.xejcjvbba {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 8v10a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2");
}

</style>
