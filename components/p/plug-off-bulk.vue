<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qvoiybbmb"/><path class="hcv6tgjxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hcv6tgjxe {
  d: path("M1.293 19.293L14 6.586V3a1 1 0 0 1 2 0v1.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-18 18a.999.999 0 1 1-1.414-1.414M10 3v4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m3 18a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

.qvoiybbmb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 6L5.438 16.562A3 3 0 0 1 5 15V9a3 3 0 0 1 3-3Zm1 3.243l1.65-1.65c.23.433.35.917.35 1.407v6a3 3 0 0 1-3 3H8.243Z");
}

</style>
