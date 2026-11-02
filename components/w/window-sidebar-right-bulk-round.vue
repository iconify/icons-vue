<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cjwdg8b7d"/><path class="bgbshn1il"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-right-bulk-round" /></template>
<style>
.bgbshn1il {
  d: path("M3 7h18a1 1 0 0 1 0 2h-5v11a1 1 0 0 1-2 0V9H3a1 1 0 0 1 0-2");
}

.cjwdg8b7d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
