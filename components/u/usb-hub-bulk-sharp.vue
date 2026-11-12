<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3p3b232l"/><path class="hkff2s1uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-hub-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hkff2s1uq {
  d: path("M13 13a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm-4 3a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm8 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Z");
}

.l3p3b232l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1M3 12h18a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1");
}

</style>
