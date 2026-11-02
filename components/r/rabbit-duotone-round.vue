<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b61n60b8k"/><path class="ayp2htb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rabbit-duotone-round" /></template>
<style>
.ayp2htb2f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21c-4 0-7-2.5-7-6c0-2.5 1-4.5 2-5c-2-1-4-4-3-6s4 0 6 4c1-.3 3-.3 4 0c2-4 5-6 6-4s-1 5-3 6c1 .5 2 2.5 2 5c0 3.5-3 6-7 6m-3-7h.01M15 14h.01M12 17h.01");
}

.b61n60b8k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.394 10.134a8.1 8.1 0 0 1-1.893-2.273c-.359-.647-.627-1.351-.726-2.086c-.103-.758-.013-1.534.331-2.222c.379-.759 1.043-1.272 1.903-1.332c.783-.054 1.532.271 2.171.697c.753.502 1.394 1.159 1.959 1.861a15 15 0 0 1 1.394 2.088c.485-.069.977-.092 1.467-.092s.982.023 1.467.092a15 15 0 0 1 1.394-2.088c.565-.702 1.206-1.359 1.959-1.861c.639-.426 1.388-.751 2.171-.697c.86.06 1.524.573 1.903 1.332c.344.688.434 1.464.331 2.222c-.099.735-.367 1.439-.726 2.086a8.1 8.1 0 0 1-1.893 2.273C19.595 11.467 20 13.368 20 15a6.6 6.6 0 0 1-.627 2.842a6.6 6.6 0 0 1-1.725 2.232C16.086 21.401 14.027 22 12 22s-4.086-.599-5.648-1.926a6.6 6.6 0 0 1-1.725-2.232A6.6 6.6 0 0 1 4 15c0-1.632.405-3.533 1.394-4.866");
}

.ft5dv1b6b {
  fill: none;
}

</style>
