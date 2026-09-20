<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kr5if0b2e"/><path class="z_iq0rbxi"/><path class="ppbx_abyw"/><path class="v-u0ijc7h"/><path class="b42rpjnun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:user-edit-duotone-regular" /></template>
<style>
.b42rpjnun {
  d: path("M14.5 16.5V14l5 -5 2.5 2.5 -5 5Z");
}

.kr5if0b2e {
  fill: currentColor;
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ppbx_abyw {
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.v-u0ijc7h {
  d: path("M3 21a6 6 0 0 1 12 0");
}

.z_iq0rbxi {
  fill: currentColor;
  d: path("M14.5 16.5V14l5 -5 2.5 2.5 -5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
