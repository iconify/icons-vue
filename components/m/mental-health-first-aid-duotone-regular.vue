<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tfz9c6maq"/><path class="xrlu58brt"/><path class="vtyuh4b7j"/><path class="uzrj-lb1g"/><path class="pohupsbfv"/><path class="f99n1fbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mental-health-first-aid-duotone-regular" /></template>
<style>
.f99n1fbkg {
  d: path("M16 7h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pohupsbfv {
  d: path("M19 4v6");
}

.tfz9c6maq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uzrj-lb1g {
  d: path("M5 21v-3c-1.5 -1.5 -2 -4 -2 -6.5a6 6 0 0 1 12 -1c0 1.5 1.5 2 1.5 3s-1 1 -1.5 1V17a1.5 1.5 0 0 1 -1.5 1.5H11V21");
}

.vtyuh4b7j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xrlu58brt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
