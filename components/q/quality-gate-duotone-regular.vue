<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="jtqx87x3m"/><path class="qrkzt8bnz"/><path class="crv4i00bu"/><path class="f3r6jjb4a"/><path class="q_47v4dkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quality-gate-duotone-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.f3r6jjb4a {
  d: path("M20 3v18");
}

.jtqx87x3m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q_47v4dkd {
  d: path("m8 12 3 3 6 -6");
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrkzt8bnz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 12 3 3 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
