<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p_0v3bbwc"/><path class="algumwb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-bulk-sharp" /></template>
<style>
.algumwb1d {
  d: path("M9 6.019V6a3.004 3.004 0 0 1 3-3h.001c1.657.001 3 1.343 2.999 3v.001A3 3 0 0 1 12 9h-.001A3 3 0 0 1 9 6.019M11.999 5a1 1 0 0 0-.711.297a.96.96 0 0 0-.288.697v.011A1 1 0 1 0 12 5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p_0v3bbwc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 7a1 1 0 0 1 .97.757l3 12A.998.998 0 0 1 20 21H4a.998.998 0 0 1-.97-1.243l3-12A1 1 0 0 1 7 7Z");
}

</style>
