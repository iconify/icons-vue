<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hm6zp_82f"/><path class="np-ovjbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hm6zp_82f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

.np-ovjbob {
  d: path("M7 2h14a1 1 0 0 1 1 1v12a1 1 0 0 1-2 0V4H8v1a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1M3.707 8.293L9.414 14h1.172l5.707-5.707a.999.999 0 1 1 1.414 1.414l-6 6A1 1 0 0 1 11 16H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414");
}

</style>
