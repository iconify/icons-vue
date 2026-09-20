<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tf_3zacif"/><path class="bpusavzao"/><path class="awe370b_p"/><path class="n674gpzmi"/><path class="g06ri4k9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pest-outline-regular" /></template>
<style>
.awe370b_p {
  d: path("m17 10 3 -3");
}

.bpusavzao {
  d: path("M7 10 4 7");
}

.g06ri4k9s {
  d: path("m17 16 3 3");
}

.n674gpzmi {
  d: path("m7 16 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tf_3zacif {
  d: path("M12 6c3 0 5 3 5 7s-2 7 -5 7 -5 -3 -5 -7 2 -7 5 -7");
}

</style>
