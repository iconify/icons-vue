<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mtp6jhbsi"/><path class="eyd7p-4li"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-check-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eyd7p-4li {
  d: path("M9.707 8.293L11 9.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M6 21v-5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v5a1 1 0 0 1-2 0v-5a1 1 0 0 0-1-1H9a1 1 0 0 0-1 1v5a1 1 0 0 1-2 0");
}

.mtp6jhbsi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 22H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h11c1.039 0 1.992.578 2.707 1.293l2 2C21.422 6.008 22 6.961 22 8v11a3 3 0 0 1-3 3");
}

</style>
