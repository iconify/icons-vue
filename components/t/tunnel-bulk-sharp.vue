<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="djbuaacrp"/><path class="ra76hubtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tunnel-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.djbuaacrp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 21v-9a4 4 0 0 0-8 0v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9C2 6.477 6.477 2 12 2s10 4.477 10 10v9a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1");
}

.ra76hubtj {
  d: path("M13 7a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-7.707-.293a.999.999 0 1 1 1.414-1.414l2 2a.999.999 0 1 1-1.414 1.414Zm12-1.414a.999.999 0 1 1 1.414 1.414l-2 2a.999.999 0 1 1-1.414-1.414ZM7 10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14 0a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2ZM7 15a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14 0a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
