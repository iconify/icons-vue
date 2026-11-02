<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v0awj1b7f"/><path class="i-nnbjblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-3-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i-nnbjblq {
  d: path("M7 10a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6 6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm6-9a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-2 14V11a1 1 0 0 1 2 0v10a1 1 0 0 1-2 0M7 21a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0Zm6 0a1 1 0 0 1-2 0v-1a1 1 0 0 1 2 0Z");
}

.v0awj1b7f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2ZM8 9a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm6 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
