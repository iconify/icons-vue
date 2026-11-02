<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xam6kbw8x"/><path class="jtacai2bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-close-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jtacai2bp {
  d: path("M16 20a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0Zm-9.707-5.707L8.586 12L6.293 9.707a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

.xam6kbw8x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
