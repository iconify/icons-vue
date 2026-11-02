<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yu5507bhi"/><path class="rqatjzbho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rqatjzbho {
  d: path("M7 3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v2h3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3Zm8 2V4H9v1Z");
}

.yu5507bhi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v15a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Z");
}

</style>
