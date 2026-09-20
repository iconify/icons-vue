<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kj_xiu02e"/><path class="a20judcsg"/><path class="e9i5dwbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mutant-kill-outline-regular" /></template>
<style>
.a20judcsg {
  d: path("m10.5 10.5 3 3");
}

.e9i5dwbzy {
  d: path("m10.5 13.5 3 -3");
}

.kj_xiu02e {
  d: path("m12 4 8 8 -8 8 -8 -8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
