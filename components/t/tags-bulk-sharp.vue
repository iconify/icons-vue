<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cz8qcsb5w"/><path class="hrn29ub0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cz8qcsb5w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5h6c.265 0 .52.105.707.293l6 6a1 1 0 0 1 0 1.414l-6 6a1 1 0 0 1-1.414 0l-6-6A1 1 0 0 1 2 12V6a1 1 0 0 1 1-1");
}

.hrn29ub0l {
  d: path("m15.707 5.293l6 6a1 1 0 0 1 0 1.414l-6 6a.999.999 0 1 1-1.414-1.414L19.586 12l-5.293-5.293a.999.999 0 1 1 1.414-1.414M7.01 9a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
