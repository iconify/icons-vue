<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hth-47bqt"/><path class="sd3hecchs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hth-47bqt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 18a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3Z");
}

.sd3hecchs {
  d: path("M3 7h18a1 1 0 0 1 0 2H10v11a1 1 0 0 1-2 0V9H3a1 1 0 0 1 0-2");
}

</style>
