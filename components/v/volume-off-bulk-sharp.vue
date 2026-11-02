<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j_tc-w5gp"/><path class="em57w9skn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.em57w9skn {
  d: path("M1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414Z");
}

.j_tc-w5gp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.414 6.172l2.879-2.879A1 1 0 0 1 15 4v6.757ZM7 7l8 8v5a1.002 1.002 0 0 1-1.707.707L9.586 17H6a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Z");
}

</style>
