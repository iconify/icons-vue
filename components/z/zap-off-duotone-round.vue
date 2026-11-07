<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="luvc6nbhq"/><path class="i30hzggpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i30hzggpv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 10l-2 2c-.369.369.262 1 1 1h2a2 2 0 0 1 2 2v4c0 .738.631 1.369 1 1l3-3m3-3l2-2c.369-.369-.262-1-1-1h-2a2 2 0 0 1-2-2V5c0-.738-.631-1.369-1-1l-3 3M2 5l17 17");
}

.luvc6nbhq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m10 7l3-3c.369-.369 1 .262 1 1v4a2.003 2.003 0 0 0 2 2h2c.738 0 1.369.631 1 1l-2 2Zm1 13c-.369.369-1-.262-1-1v-4a2.003 2.003 0 0 0-2-2H6c-.738 0-1.369-.631-1-1l2-2l7 7Z");
}

</style>
