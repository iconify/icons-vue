<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vdeccac8p"/><path class="eevg6pb8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eevg6pb8h {
  d: path("M10 7a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6-4v4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m-3 18a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

.vdeccac8p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Z");
}

</style>
