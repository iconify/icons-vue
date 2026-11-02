<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qqzy6bbyg"/><path class="n2tzskgxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n2tzskgxj {
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414l-19-19a.999.999 0 1 1 1.414-1.414M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.qqzy6bbyg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4 3l15 15H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m17 12.757L8.243 3H20a1 1 0 0 1 1 1Z");
}

</style>
