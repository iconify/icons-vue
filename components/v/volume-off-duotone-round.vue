<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gteu6_bqc"/><path class="v9-z1pb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gteu6_bqc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 17a2.32 2.32 0 0 1-1.276 2.086c-.379.19-.801.269-1.222.217a2.06 2.06 0 0 1-1.209-.596l-1-1C9.98 17.395 9.468 17 9 17H8a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l1-1a2.06 2.06 0 0 1 1.209-.596c.421-.052.843.027 1.222.217A2.32 2.32 0 0 1 15 7Z");
}

.v9-z1pb8x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h1c.64 0 1.36.36 2 1l1 1c.738.738 2 .107 2-1v-3m0-6V7c0-1.107-1.262-1.738-2-1M2 2l20 20");
}

</style>
