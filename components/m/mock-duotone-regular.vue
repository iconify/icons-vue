<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mlnbe9bja"/><path class="y76hd_85j"/><path class="n6ndjw6jf"/><path class="o9y-9tbqv"/><path class="eud-3ptuk"/><path class="kvnpcyz2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mock-duotone-regular" /></template>
<style>
.eud-3ptuk {
  d: path("M15 12h7");
}

.kvnpcyz2l {
  d: path("M15 18h7");
}

.mlnbe9bja {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n6ndjw6jf {
  d: path("M4 9h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9y-9tbqv {
  d: path("M15 6h7");
}

.y76hd_85j {
  d: path("M2 6a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
