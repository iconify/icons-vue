<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h1g3kmb0e"/><path class="wd-jkl99n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiator-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h1g3kmb0e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0Zm7 0a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0Zm7 0a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0Z");
}

.wd-jkl99n {
  d: path("M3 7h16a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m2 8h16a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

</style>
