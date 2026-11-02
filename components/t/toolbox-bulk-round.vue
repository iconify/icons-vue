<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rfsnaacsu"/><path class="zbms8gb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toolbox-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rfsnaacsu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

.zbms8gb0c {
  d: path("M11 3h2.001c1.657.001 3 1.343 2.999 3v2a1 1 0 0 1-2 0V5.998A1 1 0 0 0 13 5h-2a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0V5.999c0-.796.317-1.56.881-2.122A3 3 0 0 1 11 3M7 13v-1a1 1 0 0 1 2 0v1h6v-1a1 1 0 0 1 2 0v1h4a1 1 0 0 1 0 2h-4v1a1 1 0 0 1-2 0v-1H9v1a1 1 0 0 1-2 0v-1H3a1 1 0 0 1 0-2Z");
}

</style>
