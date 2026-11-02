<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pcb1vbcle"/><path class="em57w9skn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.em57w9skn {
  d: path("M1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414Z");
}

.pcb1vbcle {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.828 7.586l-1.414-1.414l.879-.879a2.06 2.06 0 0 1 1.209-.596c.421-.052.843.027 1.222.217A2.32 2.32 0 0 1 15 7v3.757Zm-4.7-.458L15 15v2a2.32 2.32 0 0 1-1.276 2.086c-.379.19-.801.269-1.222.217a2.06 2.06 0 0 1-1.209-.596l-1-1C9.98 17.395 9.468 17 9 17H8a3 3 0 0 1-3-3v-4c0-1.32.866-2.487 2.128-2.872");
}

</style>
