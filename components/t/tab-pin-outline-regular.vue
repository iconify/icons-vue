<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="dwto70uro"/><path class="nonq38brg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-pin-outline-regular" /></template>
<style>
.dwto70uro {
  d: path("M15 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nonq38brg {
  d: path("M18 13v3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oscmqi7_r {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
