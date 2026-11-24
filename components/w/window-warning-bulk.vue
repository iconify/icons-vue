<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hth-47bqt"/><path class="eiktrmbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-warning-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eiktrmbql {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m10 5v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m-1 5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

.hth-47bqt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 18a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3Z");
}

</style>
