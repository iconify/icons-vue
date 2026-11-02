<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xoe96qbzm"/><path class="mt_z35blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-face-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mt_z35blb {
  d: path("M2 3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0Zm19-1a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2ZM3 22a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2Zm19-1a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0Z");
}

.xoe96qbzm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.01 8a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-4.763 6.316a4.65 4.65 0 0 0 5.046-1.023a.999.999 0 1 1 1.414 1.414a6.6 6.6 0 0 1-2.203 1.462a6.6 6.6 0 0 1-2.504.488a6.6 6.6 0 0 1-2.504-.488a6.6 6.6 0 0 1-2.203-1.462a.999.999 0 1 1 1.414-1.414c.439.441.963.79 1.54 1.023");
}

</style>
