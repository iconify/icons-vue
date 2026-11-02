<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="kdrfrssuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-info-bulk-sharp" /></template>
<style>
.bpp7y5g_r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kdrfrssuj {
  d: path("M12 7h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m1 4v5a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0");
}

</style>
