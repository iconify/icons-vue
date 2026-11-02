<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="icg3rkbvd"/><path class="ldg78p3zg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webhook-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.icg3rkbvd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 7v10a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0a1 1 0 0 1-2 0a3 3 0 1 0-6 0");
}

.ldg78p3zg {
  d: path("M16 14h-2a3 3 0 0 1-3-3V7a1 1 0 0 1 2 0v4a.997.997 0 0 0 1 1h2a5 5 0 0 1 0 10a1 1 0 0 1 0-2a3 3 0 1 0 0-6m-4 2h4a1 1 0 0 1 0 2h-3.099A5.002 5.002 0 0 1 3 17a1 1 0 0 1 2 0a3 3 0 1 0 6 0a1 1 0 0 1 1-1");
}

</style>
