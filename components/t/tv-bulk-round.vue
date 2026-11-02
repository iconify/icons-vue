<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rfsnaacsu"/><path class="w5l7jjf3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tv-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rfsnaacsu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

.w5l7jjf3a {
  d: path("M8.707 3.293L12 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a.999.999 0 1 1 1.414-1.414");
}

</style>
