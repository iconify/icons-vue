<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fw1i7m28x"/><path class="hvv4899io"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toilet-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fw1i7m28x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 10h1V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v5h1a1 1 0 0 1 1 1a5.9 5.9 0 0 1-.472 2.336a6 6 0 0 1-1.285 1.907a5.97 5.97 0 0 1-3.773 1.739l1.458 3.647A.998.998 0 0 1 16 22H8a1 1 0 0 1-.928-1.371l1.458-3.647a5.98 5.98 0 0 1-3.773-1.739a6 6 0 0 1-1.285-1.907A5.9 5.9 0 0 1 3 11a1 1 0 0 1 1-1");
}

.hvv4899io {
  d: path("M4 10h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>
