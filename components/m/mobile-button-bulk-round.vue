<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dji0kcbys"/><path class="zenlmhbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-button-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dji0kcbys {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5h-2a5 5 0 0 1-5-5Z");
}

.zenlmhbbk {
  d: path("M12 17h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
