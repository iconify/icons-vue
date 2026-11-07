<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lylsadbcr"/><path class="v9-z1pb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lylsadbcr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 6c.738-.738 2-.107 2 1v1Zm2 11c0 1.107-1.262 1.738-2 1l-1-1c-.528-.527-1.227-1-2-1H8a2.003 2.003 0 0 1-2-2v-4a2.003 2.003 0 0 1 2-2l6 6Z");
}

.v9-z1pb8x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h1c.64 0 1.36.36 2 1l1 1c.738.738 2 .107 2-1v-3m0-6V7c0-1.107-1.262-1.738-2-1M2 2l20 20");
}

</style>
