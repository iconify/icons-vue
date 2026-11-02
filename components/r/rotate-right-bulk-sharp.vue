<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z0tjssmcv"/><path class="ql7npbcat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-right-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ql7npbcat {
  d: path("m9.707 2.293l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L9.586 7H6v3a1 1 0 0 1-2 0V6a1 1 0 0 1 1-1h4.586L8.293 3.707a.999.999 0 1 1 1.414-1.414M6 14v5h12V7h-2a1 1 0 0 1 0-2h3a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-6a1 1 0 0 1 2 0");
}

.z0tjssmcv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 6v14H5V6Z");
}

</style>
