<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="no7jx77av"/><path class="oomagtyxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:umbrella-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.no7jx77av {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 13H3a1 1 0 0 1-1-1C2 6.477 6.477 2 12 2s10 4.477 10 10a1 1 0 0 1-1 1");
}

.oomagtyxe {
  d: path("M13 19a1 1 0 0 0 1.387.922A.99.99 0 0 0 15 19a1 1 0 0 1 2 0a3 3 0 1 1-6 0v-7a1 1 0 0 1 2 0Z");
}

</style>
