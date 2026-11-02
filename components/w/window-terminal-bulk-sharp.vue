<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rufoxdbmp"/><path class="q_wm5ibpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-terminal-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q_wm5ibpd {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m4.707 5.293l2 2a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L7.586 15l-1.293-1.293a.999.999 0 1 1 1.414-1.414M13 16h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

.rufoxdbmp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>
