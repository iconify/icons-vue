<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j5_p9qdiu"/><path class="sbymjibxs"/><path class="q-vqg8b-v"/><path class="cim6bibwy"/><path class="d1-mj-b0m"/><path class="dj2ipwqiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:running-outline-regular" /></template>
<style>
.cim6bibwy {
  d: path("M14.5 11.5H10");
}

.d1-mj-b0m {
  d: path("m12 14 4 4v3");
}

.dj2ipwqiy {
  d: path("m12 14 -4 4H4");
}

.j5_p9qdiu {
  d: path("M13 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-vqg8b-v {
  d: path("m17 9 4 4");
}

.sbymjibxs {
  d: path("m17 9 -5 5");
}

</style>
