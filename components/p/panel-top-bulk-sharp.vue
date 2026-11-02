<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xam6kbw8x"/><path class="rt42k1imi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-top-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rt42k1imi {
  d: path("M4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

.xam6kbw8x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
