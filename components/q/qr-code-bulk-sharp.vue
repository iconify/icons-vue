<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dtkb9nb-s"/><path class="cw4fcrwag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:qr-code-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cw4fcrwag {
  d: path("M14 13h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H20a1 1 0 0 1 0-2m-5 7a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm5-3a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-1h-1a1 1 0 0 1 0-2Z");
}

.dtkb9nb-s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m10 0h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1M4 13h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

</style>
