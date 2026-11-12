<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="juhxhxtgc"/><path class="dlcjq0y-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dlcjq0y-e {
  d: path("m5.707 1.293l17 17a.999.999 0 1 1-1.414 1.414l-6.635-6.635A3 3 0 0 0 14 13h-4c-.796 0-1.559.316-2.121.879A3 3 0 0 0 7 16a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 10 11h2.586L4.293 2.707a.999.999 0 1 1 1.414-1.414");
}

.juhxhxtgc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.593 2.35C10.026 2.12 10.51 2 11 2h2a3 3 0 0 1 3 3v1a3 3 0 0 1-.761 1.997ZM5 15h2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3m13 0l4 4a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3Z");
}

</style>
