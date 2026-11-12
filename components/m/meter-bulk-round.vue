<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fo9l4tqfg"/><path class="hnn6y9d9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fo9l4tqfg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v9a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

.hnn6y9d9o {
  d: path("M9 4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM7 6h10a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m0 2v3h2V8Zm4 3h2V8h-2Zm4-3v3h2V8Zm-7 9h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
