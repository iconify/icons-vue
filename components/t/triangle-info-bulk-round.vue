<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lsxhw2bwk"/><path class="o70xbqbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-info-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lsxhw2bwk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.84 5.153l5.5 9A4.5 4.5 0 0 1 17.5 21h-11a4.5 4.5 0 0 1-3.84-6.847l5.5-9a4.502 4.502 0 0 1 7.68 0");
}

.o70xbqbae {
  d: path("M12 9h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m1 4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
