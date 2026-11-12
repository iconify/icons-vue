<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="df5n5-nbs"/><path class="dulpobc7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smart-meter-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.df5n5-nbs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

.dulpobc7h {
  d: path("M9 4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm1 2a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm-9 5V8H7v3Zm4-3h-2v3h2Zm2 3h2V8h-2Zm-6.8 5.4c.421-.56 1.063-.898 1.719-1.104A7 7 0 0 1 12 15c1.284 0 2.981.309 3.8 1.4a1 1 0 0 1-.2 1.4a1 1 0 0 1-1.4-.2a.8.8 0 0 0-.221-.181a2.3 2.3 0 0 0-.497-.215A5 5 0 0 0 12 17c-.5 0-1.004.054-1.482.204a2.3 2.3 0 0 0-.497.215a.8.8 0 0 0-.221.181a1 1 0 0 1-1.6-1.2M12 18h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
