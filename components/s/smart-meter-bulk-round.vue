<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fo9l4tqfg"/><path class="n2ka89bni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smart-meter-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fo9l4tqfg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v9a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

.n2ka89bni {
  d: path("M9 4a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm8 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM7 6h10a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m0 2v3h2V8Zm4 3h2V8h-2Zm4-3v3h2V8Zm-6.8 8.4c.421-.56 1.063-.898 1.719-1.104A7 7 0 0 1 12 15c1.284 0 2.981.309 3.8 1.4a1 1 0 0 1-.2 1.4a1 1 0 0 1-1.4-.2a.8.8 0 0 0-.221-.181a2.3 2.3 0 0 0-.497-.215A5 5 0 0 0 12 17c-.5 0-1.004.054-1.482.204a2.3 2.3 0 0 0-.497.215a.8.8 0 0 0-.221.181a1 1 0 0 1-1.6-1.2M12 18h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
