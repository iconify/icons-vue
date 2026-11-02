<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z-5yhbcwi"/><path class="ri72sacri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:speaker-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ri72sacri {
  d: path("M12 6h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m-4 8a4 4 0 1 1 8 0a4 4 0 0 1-8 0m2 0a2 2 0 1 0 3.999.001A2 2 0 0 0 10 14");
}

.z-5yhbcwi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5Z");
}

</style>
