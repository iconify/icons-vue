<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i6mxeiyqr"/><path class="dk2_9r6pl"/><path class="mm3_5jlsl"/><path class="n4vthobpf"/><path class="ujte2fbml"/><path class="exx4qg62z"/><path class="o8od38cnm"/><path class="z5iv6lbtc"/><path class="xaedo1bnv"/><path class="omq19fbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunset-header-duotone-regular" /></template>
<style>
.dk2_9r6pl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.exx4qg62z {
  d: path("M7 15a5 5 0 0 1 10 0");
}

.i6mxeiyqr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 15a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mm3_5jlsl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4.5V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n4vthobpf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 8 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8od38cnm {
  d: path("M4 18h16");
}

.omq19fbzw {
  d: path("m19 8 -2 2");
}

.ujte2fbml {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 8 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xaedo1bnv {
  d: path("m5 8 2 2");
}

.z5iv6lbtc {
  d: path("M12 4.5V7");
}

</style>
