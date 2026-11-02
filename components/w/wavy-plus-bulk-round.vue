<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ey4677bgx"/><path class="u49e6y-wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ey4677bgx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.217 8.53c2.376 1.655 2.376 5.285 0 6.94c.617 2.786-1.961 5.364-4.747 4.747c-1.655 2.376-5.285 2.376-6.94 0c-2.786.617-5.364-1.961-4.747-4.747c-2.376-1.655-2.376-5.285 0-6.94c-.617-2.786 1.961-5.364 4.747-4.747c1.655-2.376 5.285-2.376 6.94 0c2.786-.617 5.364 1.961 4.747 4.747");
}

.u49e6y-wx {
  d: path("M13 9v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2V9a1 1 0 0 1 2 0");
}

</style>
