<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d2rzqrb0o"/><path class="xafc5zbil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-barcode-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d2rzqrb0o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 16a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Zm5 0a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Z");
}

.xafc5zbil {
  d: path("M2.393 5.053a5 5 0 0 1 1.071-1.589A5 5 0 0 1 7 2a1 1 0 0 1 0 2a2.98 2.98 0 0 0-2.121.879A2.98 2.98 0 0 0 4 7a1 1 0 0 1-2 0a5 5 0 0 1 .393-1.947m16.554-2.66a5 5 0 0 1 1.589 1.071A5 5 0 0 1 22 7a1 1 0 0 1-2 0a2.98 2.98 0 0 0-.879-2.121A2.98 2.98 0 0 0 17 4a1 1 0 0 1 0-2a5 5 0 0 1 1.947.393M5.053 21.607a5 5 0 0 1-1.589-1.071A5 5 0 0 1 2 17a1 1 0 0 1 2 0a2.98 2.98 0 0 0 .879 2.121A2.98 2.98 0 0 0 7 20a1 1 0 0 1 0 2a5 5 0 0 1-1.947-.393m16.554-2.66a5 5 0 0 1-1.071 1.589A5 5 0 0 1 17 22a1 1 0 0 1 0-2a2.98 2.98 0 0 0 2.121-.879A2.98 2.98 0 0 0 20 17a1 1 0 0 1 2 0a5 5 0 0 1-.393 1.947");
}

</style>
