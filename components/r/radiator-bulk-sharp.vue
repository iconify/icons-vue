<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xfyga-bje"/><path class="wd-jkl99n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiator-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wd-jkl99n {
  d: path("M3 7h16a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m2 8h16a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

.xfyga-bje {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2h2a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m7 0h2a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m7 0h2a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
