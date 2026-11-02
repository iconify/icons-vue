<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="auh5b7b7n"/><path class="xspsx_beo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-bulk-sharp" /></template>
<style>
.auh5b7b7n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 3a1 1 0 0 1 1 1v9c0 .265-.105.52-.293.707l-7 7A1 1 0 0 1 13 21H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm-7 10v6l6-6Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.xspsx_beo {
  d: path("M20 12a1.002 1.002 0 0 1 .707 1.707l-7 7A1 1 0 0 1 12 20v-7a1 1 0 0 1 1-1Zm-2.414 2H14v3.586Z");
}

</style>
