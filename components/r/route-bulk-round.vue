<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zjfit0btt"/><path class="cv-xifokp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cv-xifokp {
  d: path("M9 7a2 2 0 1 0 0 4h6a4 4 0 0 1 0 8H8a1 1 0 0 1 0-2h7a2 2 0 1 0 0-4H9a4 4 0 0 1 0-8h6.171a3 3 0 1 1 0 2Zm8.293-.293a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.zjfit0btt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
