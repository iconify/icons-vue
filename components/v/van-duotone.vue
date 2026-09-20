<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="n34ihl8om"/><path class="f_3yqacci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:van-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f_3yqacci {
  d: path("m254.07 106.79l-45.54-53.06A16 16 0 0 0 196.26 48H32a16 16 0 0 0-16 16v112a16 16 0 0 0 16 16h17a32 32 0 0 0 62 0h50a32 32 0 0 0 62 0h17a16 16 0 0 0 16-16v-64a8 8 0 0 0-1.93-5.21M230.59 104H176V64h20.26ZM104 104V64h56v40ZM88 64v40H32V64Zm-8 136a16 16 0 1 1 16-16a16 16 0 0 1-16 16m112 0a16 16 0 1 1 16-16a16 16 0 0 1-16 16m31-24a32 32 0 0 0-62 0h-50a32 32 0 0 0-62 0H32v-56h208v56Z");
}

.n34ihl8om {
  d: path("M248 112v64a8 8 0 0 1-8 8h-24a24 24 0 0 0-48 0h-64a24 24 0 0 0-48 0H32a8 8 0 0 1-8-8v-64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
