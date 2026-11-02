<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kg5gqvb0a"/><path class="d790fjbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-duotone-sharp" /></template>
<style>
.d790fjbkx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 8.536l4.794-2.768l2 3.464L16 12l4.794 2.768l-2 3.464L14 15.464V21h-4v-5.536l-4.794 2.768l-2-3.464L8 12L3.206 9.232l2-3.464L10 8.536V3h4z");
}

.ft5dv1b6b {
  fill: none;
}

.kg5gqvb0a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 3v3.804l3.294-1.902a1 1 0 0 1 1.366.366l2 3.464a1 1 0 0 1-.366 1.366L18 12l3.294 1.902a1 1 0 0 1 .366 1.366l-2 3.464a1 1 0 0 1-1.366.366L15 17.196V21a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-3.804l-3.294 1.902a.997.997 0 0 1-1.366-.366l-2-3.464a1 1 0 0 1 .366-1.366L6 12l-3.294-1.902a1 1 0 0 1-.366-1.366l2-3.464a1 1 0 0 1 1.366-.366L9 6.804V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1");
}

</style>
