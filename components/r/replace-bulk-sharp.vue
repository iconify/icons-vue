<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="myak5xf9n"/><path class="y4cm6ovxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:replace-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.myak5xf9n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 14h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

.y4cm6ovxp {
  d: path("M5 3a1 1 0 0 1 1-1h5a1 1 0 0 1 0 2H7v3.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L5 7.586Zm9 6V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1m2-1h4V4h-4Z");
}

</style>
