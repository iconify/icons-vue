<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k-uoumeik"/><path class="u__n76blo"/><path class="m6cyaabzz"/><path class="t0l5cz7rn"/><path class="zyz2vdbji"/><path class="zrqurcb-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:schedule-report-duotone-regular" /></template>
<style>
.k-uoumeik {
  fill: currentColor;
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m6cyaabzz {
  d: path("M8 3v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t0l5cz7rn {
  d: path("M16 3v5");
}

.u__n76blo {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.zrqurcb-a {
  d: path("M5 15h8");
}

.zyz2vdbji {
  d: path("M5 11h12");
}

</style>
