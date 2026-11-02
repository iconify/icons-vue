<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s9se1bbgx"/><path class="z9ldujbtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-dim-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.s9se1bbgx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 12a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

.z9ldujbtn {
  d: path("M12.01 4a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2ZM7.05 6.05h.01a1 1 0 1 1 0 2h-.01a1 1 0 1 1 0-2m9.9 0h.01a1 1 0 0 1 0 2h-.01a1 1 0 1 1 0-2M5.01 11a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2ZM19 11h.01a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2M7.05 15.95h.01a1 1 0 1 1 0 2h-.01a1 1 0 0 1 0-2m9.9 0h.01a1 1 0 1 1 0 2h-.01a1 1 0 1 1 0-2M12.01 18a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
