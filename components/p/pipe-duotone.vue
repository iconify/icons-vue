<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="dkg5x6ezv"/><path class="bdu_ghl4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pipe-duotone" /></template>
<style>
.bdu_ghl4e {
  d: path("M232 104h-24V56h24a8 8 0 0 0 0-16h-26.17A16 16 0 0 0 192 32h-16a16 16 0 0 0-13.83 8H144A104.11 104.11 0 0 0 40 144v18.16A16 16 0 0 0 32 176v16a16 16 0 0 0 8 13.84V232a8 8 0 0 0 16 0v-24h48v24a8 8 0 0 0 16 0v-26.16a16 16 0 0 0 8-13.84v-16a16 16 0 0 0-8-13.84V144a24 24 0 0 1 24-24h18.17a16 16 0 0 0 13.83 8h16a16 16 0 0 0 13.83-8H232a8 8 0 0 0 0-16m-120 72v16H48v-16Zm-8-32v16H56v-16a88.1 88.1 0 0 1 88-88h16v48h-16a40 40 0 0 0-40 40m72-32V48h16v64Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dkg5x6ezv {
  d: path("M168 48v64h-24a32 32 0 0 0-32 32v24H48v-24a96 96 0 0 1 96-96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
