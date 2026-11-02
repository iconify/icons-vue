<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sa1fzbccq"/><path class="g9xrnybuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g9xrnybuf {
  d: path("m15 6.804l3.294-1.902a1 1 0 0 1 1.366.366l2 3.464a1 1 0 0 1-.366 1.366L18 12l3.294 1.902a1 1 0 0 1 .366 1.366l-2 3.464a1 1 0 0 1-1.366.366L15 17.196V21a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-3.804l-3.294 1.902a.997.997 0 0 1-1.366-.366l-2-3.464a1 1 0 0 1 .366-1.366L6 12l-3.294-1.902a1 1 0 0 1-.366-1.366l2-3.464a1 1 0 0 1 1.366-.366L9 6.804V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1Zm-2 1.732V4h-2v4.536a1.002 1.002 0 0 1-1.5.866L5.572 7.134l-1 1.732L8.5 11.134a1.002 1.002 0 0 1 0 1.732l-3.928 2.268l1 1.732L9.5 14.598a.998.998 0 0 1 1.5.866V20h2v-4.536a1.002 1.002 0 0 1 1.5-.866l3.928 2.268l1-1.732l-3.928-2.268a1.002 1.002 0 0 1 0-1.732l3.928-2.268l-1-1.732L14.5 9.402a.998.998 0 0 1-1.5-.866");
}

.sa1fzbccq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 2a1 1 0 0 1 1 1v3.804l3.294-1.902a1 1 0 0 1 1.366.366l2 3.464a1 1 0 0 1-.366 1.366L18 12l3.294 1.902a1 1 0 0 1 .366 1.366l-2 3.464a1 1 0 0 1-1.366.366L15 17.196V21a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-3.804l-3.294 1.902a.997.997 0 0 1-1.366-.366l-2-3.464a1 1 0 0 1 .366-1.366L6 12l-3.294-1.902a1 1 0 0 1-.366-1.366l2-3.464a1 1 0 0 1 1.366-.366L9 6.804V3a1 1 0 0 1 1-1Z");
}

</style>
