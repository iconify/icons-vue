<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q8abciafc"/><path class="j5i522b_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j5i522b_t {
  d: path("m2.707 3.293l18 18a.999.999 0 1 1-1.414 1.414L13 16.414V17a1 1 0 0 1-2 0v-2.586L1.293 4.707a.999.999 0 1 1 1.414-1.414M11 4a1 1 0 0 1 1.447-.894l6 3a1 1 0 1 1-.894 1.788L13 5.618V8a1 1 0 0 1-2 0Z");
}

.q8abciafc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.315 15.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114");
}

</style>
