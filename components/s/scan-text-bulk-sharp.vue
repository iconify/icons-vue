<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mzt9ms-iy"/><path class="mt_z35blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-text-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mt_z35blb {
  d: path("M2 3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0Zm19-1a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2ZM3 22a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2Zm19-1a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0Z");
}

.mzt9ms-iy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 7a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm-4 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
