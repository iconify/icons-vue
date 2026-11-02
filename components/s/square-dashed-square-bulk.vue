<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u1yucdb1f"/><path class="ij0sdpvcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ij0sdpvcl {
  d: path("M5 2h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0V5a3 3 0 0 1 3-3m9 2h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m8 1v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2h1a3 3 0 0 1 3 3M2 12a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm18 2v-4a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0M4 12v7a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1v-7a.997.997 0 0 0-1-1H5a.997.997 0 0 0-1 1m15 10h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0v1a3 3 0 0 1-3 3");
}

.u1yucdb1f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
