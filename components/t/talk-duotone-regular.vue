<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tfz9c6maq"/><path class="pu9i_5okb"/><path class="p9obgbnxo"/><path class="uzrj-lb1g"/><path class="i7o5y9-lr"/><path class="d-7e28zns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:talk-duotone-regular" /></template>
<style>
.d-7e28zns {
  d: path("M18 8a4 4 0 0 1 0 8");
}

.i7o5y9-lr {
  d: path("M18 10a2 2 0 0 1 0 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9obgbnxo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 8a4 4 0 0 1 0 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pu9i_5okb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 10a2 2 0 0 1 0 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tfz9c6maq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uzrj-lb1g {
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
}

</style>
