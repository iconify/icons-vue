<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nv26tqy7x"/><path class="kkcwhob7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:usb-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kkcwhob7a {
  d: path("m8.293 5.293l2.999-3a1 1 0 0 1 1.415 0l3 3a.999.999 0 1 1-1.414 1.414L13 5.414v8.172l2-2V10a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-.936-.649l-1.889 1.888a3 3 0 1 1-2.35 0l-2.431-2.43a3 3 0 1 1 .573-2.256L11 13.586V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414M5 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m14 1v-2h-2v2Zm-7.707 5.293a.999.999 0 1 0 1.414 1.414a.999.999 0 1 0-1.414-1.414");
}

.nv26tqy7x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0m13-3h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1M9 19a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
