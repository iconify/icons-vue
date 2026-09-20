<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="jrz67unam"/><path class="nz1-89h8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vector-search-outline-thin" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jrz67unam {
  d: path("m7 13 6 -6");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.nz1-89h8c {
  d: path("M10 7h3v3");
}

</style>
