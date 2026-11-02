<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="av2t1p2fx"/><path class="u4z6b_b8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-receiver-bulk-round" /></template>
<style>
.av2t1p2fx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 13a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u4z6b_b8h {
  d: path("m6.486 8.143l10-6a1 1 0 0 1 1.371.343a1 1 0 0 1-.343 1.371l-10 6a1 1 0 0 1-1.371-.343a1 1 0 0 1 .343-1.371M6 15a3 3 0 1 1 6 0a3 3 0 0 1-6 0m11-3a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm-9 3a1 1 0 1 0 2 0a1 1 0 0 0-2 0m7 1h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2");
}

</style>
