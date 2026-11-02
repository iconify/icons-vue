<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gd-4pggfu"/><path class="ri72sacri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:speaker-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gd-4pggfu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.ri72sacri {
  d: path("M12 6h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m-4 8a4 4 0 1 1 8 0a4 4 0 0 1-8 0m2 0a2 2 0 1 0 3.999.001A2 2 0 0 0 10 14");
}

</style>
