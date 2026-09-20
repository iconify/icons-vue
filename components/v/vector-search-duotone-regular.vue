<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="k2e53zb1b"/><path class="l3_z0f2kq"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="jrz67unam"/><path class="nz1-89h8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vector-search-duotone-regular" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.jrz67unam {
  d: path("m7 13 6 -6");
}

.k2e53zb1b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 13 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.l3_z0f2kq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 7h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nz1-89h8c {
  d: path("M10 7h3v3");
}

.qa-jr78us {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vxtvt1e5w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
