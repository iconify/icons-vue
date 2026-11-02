<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wlf3tlvuj"/><path class="xkmvyzbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microwave-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wlf3tlvuj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.xkmvyzbdv {
  d: path("M6 9a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2Zm12-1v6a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0M8 9v4h4V9Zm0 9v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0m10 0v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0");
}

</style>
