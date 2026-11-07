<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w3x7f__zv"/><path class="ylnl7qbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-eye-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.w3x7f__zv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.779 7.78c2.704-1.708 5.738-1.708 8.442 0c1.466.926 2.654 2.23 3.611 3.665a1 1 0 0 1 0 1.11c-.957 1.435-2.145 2.739-3.611 3.665c-2.704 1.708-5.738 1.708-8.442 0c-1.466-.926-2.654-2.23-3.611-3.665a1 1 0 0 1 0-1.11c.957-1.435 2.145-2.739 3.611-3.665M6.221 12c3.442 4.664 8.116 4.664 11.558 0c-3.442-4.664-8.116-4.664-11.558 0m5.789-1a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.ylnl7qbae {
  d: path("M2.393 5.053a5 5 0 0 1 1.071-1.589A5 5 0 0 1 7 2a1 1 0 0 1 0 2a2.98 2.98 0 0 0-2.121.879A2.98 2.98 0 0 0 4 7a1 1 0 0 1-2 0a5 5 0 0 1 .393-1.947m16.554-2.66a5 5 0 0 1 1.589 1.071A5 5 0 0 1 22 7a1 1 0 0 1-2 0a2.98 2.98 0 0 0-.879-2.121A2.98 2.98 0 0 0 17 4a1 1 0 0 1 0-2a5 5 0 0 1 1.947.393M12 11h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2M5.053 21.607a5 5 0 0 1-1.589-1.071A5 5 0 0 1 2 17a1 1 0 0 1 2 0a2.98 2.98 0 0 0 .879 2.121A2.98 2.98 0 0 0 7 20a1 1 0 0 1 0 2a5 5 0 0 1-1.947-.393m16.554-2.66a5 5 0 0 1-1.071 1.589A5 5 0 0 1 17 22a1 1 0 0 1 0-2a2.98 2.98 0 0 0 2.121-.879A2.98 2.98 0 0 0 20 17a1 1 0 0 1 2 0a5 5 0 0 1-.393 1.947");
}

</style>
