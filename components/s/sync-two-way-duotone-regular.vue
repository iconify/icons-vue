<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v7z0k1hgy"/><path class="ge_8z_kcu"/><path class="ss5zaeetb"/><path class="o6qjnwbdf"/><path class="h5m00ybuy"/><path class="ap_bu5bso"/><path class="z5anc_e2t"/><path class="xj9o_6b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sync-two-way-duotone-regular" /></template>
<style>
.ap_bu5bso {
  d: path("m15 6 3 3 -3 3");
}

.ge_8z_kcu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h5m00ybuy {
  d: path("M4 9h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o6qjnwbdf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 12 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ss5zaeetb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v7z0k1hgy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xj9o_6b5o {
  d: path("m9 12 -3 3 3 3");
}

.z5anc_e2t {
  d: path("M6 15h14");
}

</style>
