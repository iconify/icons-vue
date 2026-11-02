<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y_a6fjfyi"/><path class="aib9okb5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vault-bulk-sharp" /></template>
<style>
.aib9okb5v {
  d: path("M7 11a5 5 0 1 1 10.001.001A5 5 0 0 1 7 11m2 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3-1h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2M8 21a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm10 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.y_a6fjfyi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
