<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oi0er2bgl"/><path class="h_jck4npl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-capricorn-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h_jck4npl {
  d: path("M8.144 4.2a4 4 0 0 1 4.37-.902A3.99 3.99 0 0 1 15 7v11a3.98 3.98 0 0 1-1.172 2.828A3.98 3.98 0 0 1 11 22a1 1 0 0 1 0-2a2 2 0 0 0 2-2V7a2 2 0 1 0-4 0v9a1 1 0 0 1-2 0V7a3 3 0 0 0-3-3a1 1 0 0 1 0-2a5 5 0 0 1 1.947.393A5.05 5.05 0 0 1 8.144 4.2");
}

.oi0er2bgl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 14.999a2 2 0 1 0 4 .002a2 2 0 0 0-4-.003m-2 .003a4 4 0 1 1 8-.004a4 4 0 0 1-8 .006");
}

</style>
