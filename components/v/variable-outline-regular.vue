<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wf6zu9b6f"/><path class="n7sdxmqqs"/><path class="gq7a04b8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:variable-outline-regular" /></template>
<style>
.gq7a04b8r {
  d: path("M14 14h5");
}

.n7sdxmqqs {
  d: path("M14 11h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wf6zu9b6f {
  d: path("M2 9a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
