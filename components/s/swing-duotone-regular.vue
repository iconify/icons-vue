<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mj-457o_e"/><path class="d0rcyrckg"/><path class="lge0xr18z"/><path class="txii_1wlf"/><path class="e99hiubds"/><path class="h3aib2b4u"/><path class="qsabb4b5g"/><path class="dihddo_by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swing-duotone-regular" /></template>
<style>
.d0rcyrckg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dihddo_by {
  d: path("M6 18h12");
}

.e99hiubds {
  d: path("M5 3h14");
}

.h3aib2b4u {
  d: path("M8 3v15");
}

.lge0xr18z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mj-457o_e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 3h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qsabb4b5g {
  d: path("M16 3v15");
}

.txii_1wlf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
