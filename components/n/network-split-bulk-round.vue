<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j6-cpacfl"/><path class="mjpc89b7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-split-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j6-cpacfl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.mjpc89b7w {
  d: path("M11 7a1 1 0 0 1 2 0v4h1a5 5 0 0 1 5 5v1.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L17 17.586V16a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v1.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.413.001h-.001l-3-3.001a.999.999 0 1 1 1.414-1.414L5 17.586V16a5 5 0 0 1 5-5h1Z");
}

</style>
