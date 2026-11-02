<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oln7ajmrv"/><path class="ik13q-bgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-pine-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ik13q-bgm {
  d: path("M13 18v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0");
}

.oln7ajmrv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 8a1 1 0 0 1-.625-1.781l5-4a1 1 0 0 1 1.25 0l5 4A1.002 1.002 0 0 1 17 8h-.586l2.293 2.293a1.34 1.34 0 0 1 .382 1.186c-.138.815-.932 1.361-1.706 1.49l3.324 3.324c.311.31.456.752.382 1.186C20.928 18.428 19.898 19 19 19H5c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l3.324-3.324c-.774-.129-1.568-.675-1.706-1.49a1.34 1.34 0 0 1 .382-1.186L7.586 8Z");
}

</style>
