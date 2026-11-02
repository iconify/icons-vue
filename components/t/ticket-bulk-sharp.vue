<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bixu74c8y"/><path class="kq9dphvtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-bulk-sharp" /></template>
<style>
.bixu74c8y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 9a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kq9dphvtl {
  d: path("M15 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>
