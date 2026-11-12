<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n4hg83b2o"/><path class="ne_a8sbqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-lock-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n4hg83b2o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 16V8a5 5 0 0 1 5-5h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 8a1 1 0 0 1-1 1Z");
}

.ne_a8sbqi {
  d: path("M14 15.171V15a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 18v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1c0-1.27.803-2.405 2-2.829M16 15h2a1 1 0 0 0-2 0");
}

</style>
