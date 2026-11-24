<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hhum8kbmu"/><path class="fx1s1bbzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-edit-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fx1s1bbzs {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m9 14v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

.hhum8kbmu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1");
}

</style>
