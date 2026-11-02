<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ud70w6wcd"/><path class="nxxkiebtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rabbit-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nxxkiebtj {
  d: path("M9.01 13a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-3 3a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

.ud70w6wcd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.394 10.134a8.1 8.1 0 0 1-1.893-2.273c-.359-.647-.627-1.351-.726-2.086c-.103-.758-.013-1.534.331-2.222c.379-.759 1.043-1.272 1.903-1.332c.783-.054 1.532.271 2.171.697c.753.502 1.394 1.159 1.959 1.861a15 15 0 0 1 1.394 2.088c.485-.069.977-.092 1.467-.092s.982.023 1.467.092a15 15 0 0 1 1.394-2.088c.565-.702 1.206-1.359 1.959-1.861c.639-.426 1.388-.751 2.171-.697c.86.06 1.524.573 1.903 1.332c.344.688.434 1.464.331 2.222c-.099.735-.367 1.439-.726 2.086a8.1 8.1 0 0 1-1.893 2.273C19.595 11.467 20 13.368 20 15a6.6 6.6 0 0 1-.627 2.842a6.6 6.6 0 0 1-1.725 2.232C16.086 21.401 14.027 22 12 22s-4.086-.599-5.648-1.926a6.6 6.6 0 0 1-1.725-2.232A6.6 6.6 0 0 1 4 15c0-1.632.405-3.533 1.394-4.866");
}

</style>
