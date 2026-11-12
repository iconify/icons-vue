<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p05d90bur"/><path class="zee8uibzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-clock-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p05d90bur {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m6 8v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

.zee8uibzt {
  d: path("M11 17a6 6 0 1 1 12 0a6 6 0 0 1-12 0m2.025.452a4 4 0 1 0 7.95-.905a4 4 0 0 0-7.95.905M2 21c0-1.862.731-3.636 2.05-4.95a7 7 0 0 1 2.225-1.5A6.9 6.9 0 0 1 9 14a1 1 0 0 1 0 2a4.97 4.97 0 0 0-3.536 1.464A4.97 4.97 0 0 0 4 21a1 1 0 0 1-2 0m17-3h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v1h1a1 1 0 0 1 0 2");
}

</style>
