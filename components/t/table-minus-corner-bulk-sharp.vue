<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gpbwylboe"/><path class="xzpcydfzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-minus-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gpbwylboe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 3a1 1 0 0 1 1 1v5H10v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

.xzpcydfzu {
  d: path("M13 4v4h7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h7V4a1 1 0 0 1 2 0M9 14a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm12 1a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
