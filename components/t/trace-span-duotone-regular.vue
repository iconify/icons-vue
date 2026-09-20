<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tvqildb1v"/><path class="ge02uk2xx"/><path class="uwn-88-lo"/><path class="crv4i00bu"/><path class="gxfvqwb6p"/><path class="mpqxuepwm"/><path class="lc1sr-eqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trace-span-duotone-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.ge02uk2xx {
  fill: currentColor;
  d: path("M10 13a1.5 1.5 0 0 1 1.5 -1.5h9A1.5 1.5 0 0 1 22 13a1.5 1.5 0 0 1 -1.5 1.5h-9A1.5 1.5 0 0 1 10 13");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gxfvqwb6p {
  d: path("M7 7a1.5 1.5 0 0 1 1.5 -1.5h10A1.5 1.5 0 0 1 20 7a1.5 1.5 0 0 1 -1.5 1.5h-10A1.5 1.5 0 0 1 7 7");
}

.lc1sr-eqo {
  d: path("M7 19a1.5 1.5 0 0 1 1.5 -1.5h4A1.5 1.5 0 0 1 14 19a1.5 1.5 0 0 1 -1.5 1.5h-4A1.5 1.5 0 0 1 7 19");
}

.mpqxuepwm {
  d: path("M10 13a1.5 1.5 0 0 1 1.5 -1.5h9A1.5 1.5 0 0 1 22 13a1.5 1.5 0 0 1 -1.5 1.5h-9A1.5 1.5 0 0 1 10 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tvqildb1v {
  fill: currentColor;
  d: path("M7 7a1.5 1.5 0 0 1 1.5 -1.5h10A1.5 1.5 0 0 1 20 7a1.5 1.5 0 0 1 -1.5 1.5h-10A1.5 1.5 0 0 1 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uwn-88-lo {
  fill: currentColor;
  d: path("M7 19a1.5 1.5 0 0 1 1.5 -1.5h4A1.5 1.5 0 0 1 14 19a1.5 1.5 0 0 1 -1.5 1.5h-4A1.5 1.5 0 0 1 7 19");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
