<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dfexzobhe"/><path class="bmxevhbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ungroup-bulk-sharp" /></template>
<style>
.bmxevhbix {
  d: path("M11 14a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1Zm2 4h5v-3h-5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dfexzobhe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

</style>
