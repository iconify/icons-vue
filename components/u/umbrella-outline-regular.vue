<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="o162teb3v"/><path class="cr8isx4cy"/><path class="jzkjbccbo"/><path class="e2nq-yvbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:umbrella-outline-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.cr8isx4cy {
  d: path("M15 12a3 3 0 0 1 -6 0");
}

.e2nq-yvbg {
  d: path("M12 15v6");
}

.jzkjbccbo {
  d: path("M21 12a3 3 0 0 1 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o162teb3v {
  d: path("M9 12a3 3 0 0 1 -6 0");
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

</style>
