<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="jilhl854s"/><path class="hqxuxsrnp"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="jrz67unam"/><path class="nz1-89h8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vector-search-duotone-thin" /></template>
<style>
.dba5rjonf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

.hqxuxsrnp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 7h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jilhl854s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 13 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.zl5hlnbpt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
