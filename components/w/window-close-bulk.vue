<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hth-47bqt"/><path class="flqxwpbvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.flqxwpbvu {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m7.707 5.293L12 13.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 15l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 16.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 15l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.hth-47bqt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 18a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3Z");
}

</style>
