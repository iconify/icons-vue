<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lnef9ckzr"/><path class="hgzn2c7we"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-user-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hgzn2c7we {
  d: path("M9.236 7.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m-3.529 6.502a5.165 5.165 0 0 1 9.196 1.511a1 1 0 0 1-1.92.56a3.165 3.165 0 0 0-6.08 0a1 1 0 0 1-1.92-.56c.157-.54.401-1.051.724-1.511");
}

.lnef9ckzr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2h8a5 5 0 0 1 5 5v3c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V7a5 5 0 0 1 5-5");
}

</style>
