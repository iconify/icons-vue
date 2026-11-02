<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cxj180bbo"/><path class="ys39zsbnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tram-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cxj180bbo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 6h6a5 5 0 0 1 5 5v6a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-6a5 5 0 0 1 5-5m-3 6h12v-1a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3Z");
}

.ys39zsbnb {
  d: path("M9 2h6a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0V4H9a1 1 0 0 1 0-2m0 13h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-7.106 6.447a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894Zm10-.894a1 1 0 1 1-1.788.894l-1-2a1 1 0 1 1 1.788-.894Z");
}

</style>
