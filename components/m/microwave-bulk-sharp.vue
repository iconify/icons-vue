<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xdtcfdboh"/><path class="r2ivfsbtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microwave-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r2ivfsbtd {
  d: path("M6 14V8a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1m12-6v6a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0M8 9v4h4V9Zm0 9v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0m10 0v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0");
}

.xdtcfdboh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>
