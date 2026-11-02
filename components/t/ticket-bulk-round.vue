<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zz3jffbbq"/><path class="kq9dphvtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ticket-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kq9dphvtl {
  d: path("M15 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

.zz3jffbbq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 19H6a4 4 0 0 1-4-4a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1a4 4 0 0 1 4-4h12a4 4 0 0 1 4 4a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1a4 4 0 0 1-4 4");
}

</style>
