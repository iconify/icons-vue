<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p05d90bur"/><path class="nlw5_0bmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-pin-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nlw5_0bmd {
  d: path("M14 12h6a1 1 0 0 1 0 2v1.586l.707.707c.311.31.456.752.382 1.186C20.928 18.428 19.898 19 19 19h-1v2a1 1 0 0 1-2 0v-2h-1c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l.707-.707V14a1 1 0 0 1 0-2M2.55 18.275a7 7 0 0 1 1.5-2.225a7 7 0 0 1 2.225-1.5A6.9 6.9 0 0 1 9 14a1 1 0 0 1 0 2a4.97 4.97 0 0 0-3.536 1.464A4.97 4.97 0 0 0 4 21a1 1 0 0 1-2 0a6.9 6.9 0 0 1 .55-2.725");
}

.p05d90bur {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m6 8v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

</style>
