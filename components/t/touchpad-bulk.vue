<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="trdjr4bpx"/><path class="dqa_u8b9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:touchpad-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dqa_u8b9n {
  d: path("M12 13h9a1 1 0 0 1 0 2h-8v4a1 1 0 0 1-2 0v-4H3a1 1 0 0 1 0-2Z");
}

.trdjr4bpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
