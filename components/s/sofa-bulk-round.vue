<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u2tevccak"/><path class="x62iz2bto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u2tevccak {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a2.999 2.999 0 0 1 5.121-2.121c.274.273.493.596.643.953c.157.369.237.767.236 1.168a.997.997 0 0 0 1 1h6a.997.997 0 0 0 1-1a3 3 0 0 1 .236-1.168A2.998 2.998 0 0 1 22 11v2a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

.x62iz2bto {
  d: path("M9 4h6a4.98 4.98 0 0 1 3.536 1.464A5 5 0 0 1 20 9a1 1 0 0 1-2 0a3.004 3.004 0 0 0-3-3h-2v7a1 1 0 0 1-2 0V6H9a3.004 3.004 0 0 0-3 3a1 1 0 0 1-2 0a4.995 4.995 0 0 1 5-5M6 19a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Zm14 0a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0Z");
}

</style>
