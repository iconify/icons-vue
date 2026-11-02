<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uzcfpfb-m"/><path class="s95zvrsyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.s95zvrsyk {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

.uzcfpfb-m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8c0-.155.036-.308.106-.447l2-4A1 1 0 0 1 6 3h12c.379 0 .725.214.894.553l2 4c.07.139.106.292.106.447v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
