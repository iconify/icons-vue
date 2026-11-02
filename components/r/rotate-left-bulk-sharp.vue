<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k97584zbd"/><path class="t4z28vb-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k97584zbd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6h14v14H5Z");
}

.t4z28vb-y {
  d: path("M15.707 3.707L14.414 5H19a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V7h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414M20 14v6a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H6v12h12v-5a1 1 0 0 1 2 0");
}

</style>
