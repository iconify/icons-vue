<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iz70slbkn"/><path class="wro3hhbbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-clock-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iz70slbkn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2.684 5.051l9-3a1.001 1.001 0 0 1 1.265 1.265l-3 9a1 1 0 0 1-1.843.131L6.255 8.745L2.553 6.894a1 1 0 0 1 .131-1.843");
}

.wro3hhbbz {
  d: path("m6.293 7.293l1-1a.999.999 0 1 1 1.414 1.414l-1 1a.999.999 0 1 1-1.414-1.414M11 17.002v-.004a6 6 0 1 1 12-.004a6 6 0 0 1-12 .008m2.026-.464a4 4 0 1 0 7.947.923a4 4 0 0 0-7.947-.923M16 17v-2a1 1 0 0 1 2 0v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1");
}

</style>
