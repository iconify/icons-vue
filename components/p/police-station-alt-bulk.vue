<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x5rg_r_va"/><path class="uxfgtqs4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uxfgtqs4p {
  d: path("M9.75 5h4.5c.966 0 1.75.784 1.75 1.75v1.875c-.001 2.409-1.475 4.097-3.594 5.039a1 1 0 0 1-.812 0C9.475 12.722 8.001 11.034 8 8.625V6.75C8 5.784 8.784 5 9.75 5M21 22H3a1 1 0 0 1 0-2h6v-1a3 3 0 1 1 6 0v1h6a1 1 0 0 1 0 2m-8-2v-1a1 1 0 0 0-2 0v1Z");
}

.x5rg_r_va {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 22H5a1 1 0 0 1-1-1V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v16a1 1 0 0 1-1 1");
}

</style>
