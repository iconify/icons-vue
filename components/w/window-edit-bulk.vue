<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hth-47bqt"/><path class="b9230rjdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-edit-bulk" /></template>
<style>
.b9230rjdv {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m5 8c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 .159 1.207a1 1 0 0 1-.159 1.207l-4 4A1 1 0 0 1 11 19H9a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hth-47bqt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 18a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3Z");
}

</style>
