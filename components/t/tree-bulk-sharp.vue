<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yvnxgvb1b"/><path class="x_lv4nmav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.x_lv4nmav {
  d: path("M9.707 10.293L12 12.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L13 14.414V21a1 1 0 0 1-2 0v-6.586l-2.707-2.707a.999.999 0 1 1 1.414-1.414");
}

.yvnxgvb1b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.625 5.081a4.603 4.603 0 0 1 3.451 5.893a5.202 5.202 0 0 1-5.1 7.026H9.024a5.202 5.202 0 0 1-5.1-7.026a4.603 4.603 0 0 1 3.451-5.893a5.503 5.503 0 0 1 9.25 0");
}

</style>
