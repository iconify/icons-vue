<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="demqk_b8r"/><path class="awyi7ubmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:percent-bulk-sharp" /></template>
<style>
.awyi7ubmy {
  d: path("M5.707 19.707a.999.999 0 1 1-1.414-1.414l14-14a.999.999 0 1 1 1.414 1.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.demqk_b8r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.236 5.832A3 3 0 1 1 9.763 8.17a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m7.943 8.125a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

</style>
