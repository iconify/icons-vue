<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n4hg83b2o"/><path class="mwkzsnb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-star-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mwkzsnb2h {
  d: path("m12.859 15.21l2.281-.326l.966-1.931a.998.998 0 0 1 1.788 0l.966 1.931l2.281.326a1.001 1.001 0 0 1 .566 1.697l-1.636 1.636l.315 1.893a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L17 20.518l-1.953.976a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.315-1.893l-1.636-1.636a1.001 1.001 0 0 1 .566-1.697");
}

.n4hg83b2o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 16V8a5 5 0 0 1 5-5h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 8a1 1 0 0 1-1 1Z");
}

</style>
