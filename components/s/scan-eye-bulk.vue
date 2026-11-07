<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w3x7f__zv"/><path class="gz4dk8ldn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-eye-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gz4dk8ldn {
  d: path("M2 5a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0Zm17-3a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-2a1 1 0 0 1 0-2Zm-7 9h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2M5 22a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2Zm17-3a3 3 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0Z");
}

.w3x7f__zv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.779 7.78c2.704-1.708 5.738-1.708 8.442 0c1.466.926 2.654 2.23 3.611 3.665a1 1 0 0 1 0 1.11c-.957 1.435-2.145 2.739-3.611 3.665c-2.704 1.708-5.738 1.708-8.442 0c-1.466-.926-2.654-2.23-3.611-3.665a1 1 0 0 1 0-1.11c.957-1.435 2.145-2.739 3.611-3.665M6.221 12c3.442 4.664 8.116 4.664 11.558 0c-3.442-4.664-8.116-4.664-11.558 0m5.789-1a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
