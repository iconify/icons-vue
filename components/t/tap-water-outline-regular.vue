<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hcbxlsosl"/><path class="pdlat6brq"/><path class="z4g4wjbvf"/><path class="spjil5bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tap-water-outline-regular" /></template>
<style>
.hcbxlsosl {
  d: path("M4 6h8v6h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pdlat6brq {
  d: path("M9 3v3");
}

.spjil5bml {
  d: path("m16 13 3 3a3 3 0 0 1 -6 0Z");
}

.z4g4wjbvf {
  d: path("M6 3h6");
}

</style>
