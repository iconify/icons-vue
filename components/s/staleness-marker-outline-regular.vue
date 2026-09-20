<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x3ookvx2e"/><path class="kuui-zbsa"/><path class="c08_j9b_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staleness-marker-outline-regular" /></template>
<style>
.c08_j9b_a {
  d: path("m19.5 11.5 -3 3");
}

.kuui-zbsa {
  d: path("m16.5 11.5 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.x3ookvx2e {
  d: path("m7 17 4 -4h3");
}

</style>
