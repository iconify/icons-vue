<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kos1gu6xe"/><path class="veohw4byc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subway-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kos1gu6xe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 12v5a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-5a6 6 0 1 1 12 0m-3.045-2.696a4 4 0 0 0-5.705-.207l-.001.001A4 4 0 0 0 8.127 11h7.746a4 4 0 0 0-.918-1.696");
}

.veohw4byc {
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10v9a1 1 0 0 1-2 0v-9a8 8 0 0 0-16 0v9a1 1 0 0 1-2 0Zm8 2h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-4.106 7.447a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894Zm6-.894a1 1 0 1 1-1.788.894l-1-2a1 1 0 1 1 1.788-.894Z");
}

</style>
