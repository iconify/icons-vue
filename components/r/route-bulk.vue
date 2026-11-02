<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zjfit0btt"/><path class="zchlg01jl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.zchlg01jl {
  d: path("M8 7a1 1 0 0 0-1 1v2a.997.997 0 0 0 1 1h8a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H8a1 1 0 0 1 0-2h8a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1H8a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3h7.171a3 3 0 1 1 0 2Zm9.293-.293a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.zjfit0btt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
