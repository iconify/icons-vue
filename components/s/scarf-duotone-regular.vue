<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zbr-9048r"/><path class="l8kel8bqt"/><path class="k9yvujbju"/><path class="oz3eccbug"/><path class="ls_1jlbjr"/><path class="mhf9v2bnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scarf-duotone-regular" /></template>
<style>
.k9yvujbju {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 11v10h4V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l8kel8bqt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 8v10h4V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ls_1jlbjr {
  d: path("M7 8v10h4V8");
}

.mhf9v2bnf {
  d: path("M14 11v10h4V11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oz3eccbug {
  d: path("M7 8a5 5 0 0 1 10 0");
}

.zbr-9048r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 8a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
