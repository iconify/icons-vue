<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nyo0sgxgn"/><path class="oewjtrp_y"/><path class="jf0dusbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:whistle-outline-regular" /></template>
<style>
.jf0dusbyh {
  d: path("M16 10h5v3h-5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nyo0sgxgn {
  d: path("M9 6c4 0 7 3 7 7 0 3 -3 6 -7 6s-6 -3 -6 -6c0 -4 2 -7 6 -7");
}

.oewjtrp_y {
  d: path("M7 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
