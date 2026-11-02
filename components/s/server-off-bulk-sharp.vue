<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eb4o0mb6v"/><path class="nerdhbb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eb4o0mb6v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3 3l8 8H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m4.243 0H21a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-5.757ZM21 21H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h10Zm1-3.243L17.243 13H21a1 1 0 0 1 1 1Z");
}

.nerdhbb1y {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414M7 16h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
