<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gjx_cybnq"/><path class="m7b08xyfb"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-email-outline-regular" /></template>
<style>
.cfyvl-o0i {
  d: path("M16 12h4");
}

.gjx_cybnq {
  d: path("M2 10a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.m7b08xyfb {
  d: path("m4 9 3.5 3.5L11 9");
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
