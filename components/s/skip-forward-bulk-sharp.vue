<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p873_qbny"/><path class="fwp9lvbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fwp9lvbrl {
  d: path("M21 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

.p873_qbny {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.504 4.136l12 7a1 1 0 0 1 0 1.728l-12 7A1.002 1.002 0 0 1 3 19V5a.998.998 0 0 1 1.504-.864");
}

</style>
