<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="djfohilqu"/><path class="u4z6b_b8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-receiver-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.djfohilqu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.u4z6b_b8h {
  d: path("m6.486 8.143l10-6a1 1 0 0 1 1.371.343a1 1 0 0 1-.343 1.371l-10 6a1 1 0 0 1-1.371-.343a1 1 0 0 1 .343-1.371M6 15a3 3 0 1 1 6 0a3 3 0 0 1-6 0m11-3a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm-9 3a1 1 0 1 0 2 0a1 1 0 0 0-2 0m7 1h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2");
}

</style>
