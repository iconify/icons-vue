<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sf2uf-b4k"/><path class="bddse8o8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:orbit-bulk" /></template>
<style>
.bddse8o8o {
  d: path("M5.639 15.068a3 3 0 1 1-2.058.288a9.063 9.063 0 0 1 9.537-12.349l.006.001a.999.999 0 1 1-.248 1.984h-.004a7.063 7.063 0 0 0-7.233 10.076m14.78-6.424a9.1 9.1 0 0 1 .574 4.474l-.001.006a9.06 9.06 0 0 1-10.116 7.868a1 1 0 0 1-.868-1.116v-.005a1 1 0 0 1 1.116-.863h.004a7.06 7.06 0 0 0 6.61-2.894a7.05 7.05 0 0 0 .623-7.182a3 3 0 1 1 2.058-.288");
}

.cuyn6tgcc {
  fill: currentColor;
}

.sf2uf-b4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-8 6a4 4 0 1 1 8 0a4 4 0 0 1-8 0m-6 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
