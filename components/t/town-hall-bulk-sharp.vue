<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d4layjbzh"/><path class="kgdtkqjfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:town-hall-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d4layjbzh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 8a6 6 0 1 1 12 0v6h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h3Z");
}

.kgdtkqjfy {
  d: path("M6 8a6 6 0 1 1 12 0A6 6 0 0 1 6 8m9.686-1.557a4.001 4.001 0 1 0-7.37 3.116a4.001 4.001 0 0 0 7.37-3.116M13 7h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1V6a1 1 0 0 1 2 0ZM9 17a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3h-2v3a1 1 0 0 1-2 0Z");
}

</style>
