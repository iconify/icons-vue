<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qu5lrmbhn"/><path class="rt42k1imi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-top-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qu5lrmbhn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 16a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5Z");
}

.rt42k1imi {
  d: path("M4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>
