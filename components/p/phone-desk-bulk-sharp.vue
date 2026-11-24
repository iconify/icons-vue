<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p4nutbi4q"/><path class="hel9fcb0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-desk-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hel9fcb0r {
  d: path("M15 2h6a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m1 18h4V4h-4ZM12 8a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm-5.99 4a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm-6 3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.p4nutbi4q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 2h6a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1v-1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h11V3a1 1 0 0 1 1-1");
}

</style>
