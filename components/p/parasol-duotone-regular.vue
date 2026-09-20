<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z3k3a4gqp"/><path class="l8eb96b5n"/><path class="n0xh97d3q"/><path class="t9gnp4b0n"/><path class="atsab9b_m"/><path class="qxhe48bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parasol-duotone-regular" /></template>
<style>
.atsab9b_m {
  d: path("M3 12q3 3 6 0 3 3 6 0 3 3 6 0");
}

.l8eb96b5n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12q3 3 6 0 3 3 6 0 3 3 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n0xh97d3q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 14v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qxhe48bjs {
  d: path("M12 14v7");
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.z3k3a4gqp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
