<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="grze2uyki"/><path class="popaz21gp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.grze2uyki {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 17v1a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h1Zm5.218.976L8.243 5H15a1 1 0 0 1 1 1v2.382l4.553-2.276A1 1 0 0 1 22 7v10a1 1 0 0 1-.782.976");
}

.popaz21gp {
  d: path("M1.293 3.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
