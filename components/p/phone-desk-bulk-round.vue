<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ky5noiiyz"/><path class="azscdebjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-desk-bulk-round" /></template>
<style>
.azscdebjq {
  d: path("M17 2h2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m0 18h2a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-2a.997.997 0 0 0-1 1v14a1 1 0 0 0 1 1M12 8a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm-5.99 4a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm-6 3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm3 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ky5noiiyz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.171 4A3 3 0 0 1 17 2h2a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-2a3 3 0 0 1-2.829-2H6a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4Z");
}

</style>
