<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nyzdfrksg"/><path class="ux62gzu1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-clock-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nyzdfrksg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

.ux62gzu1d {
  d: path("M11 16.998a6 6 0 1 1 12-.004a6 6 0 0 1-12 .008V17ZM13 17a4 4 0 1 0 8 0a4 4 0 0 0-8 0m3-2a1 1 0 0 1 2 0v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1Z");
}

</style>
