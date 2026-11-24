<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uuittcc3u"/><path class="yl78ecc6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uuittcc3u {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 22H5a1 1 0 0 1-1-1V7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v14a1 1 0 0 1-1 1");
}

.yl78ecc6f {
  d: path("M10.5 5h3A2.5 2.5 0 0 1 16 7.5v1.125c-.001 2.409-1.475 4.097-3.594 5.039a1 1 0 0 1-.812 0C9.475 12.722 8.001 11.034 8 8.625V7.5A2.5 2.5 0 0 1 10.5 5M21 22H3a1 1 0 0 1 0-2h6v-1a3 3 0 1 1 6 0v1h6a1 1 0 0 1 0 2m-8-2v-1a1 1 0 0 0-2 0v1Z");
}

</style>
