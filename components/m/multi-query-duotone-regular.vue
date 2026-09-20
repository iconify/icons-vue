<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="emm8dqgmc"/><path class="olim7isja"/><path class="bccp-h04c"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="gjllsvbkd"/><path class="g-zzhsbrv"/><path class="r_4k1sbsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multi-query-duotone-regular" /></template>
<style>
.bccp-h04c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.emm8dqgmc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.g-zzhsbrv {
  d: path("M7 10h6");
}

.gjllsvbkd {
  d: path("M7 7h6");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olim7isja {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qa-jr78us {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r_4k1sbsg {
  d: path("M7 13h6");
}

.vxtvt1e5w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
