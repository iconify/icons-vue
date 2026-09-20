<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsy-y08mq"/><path class="sixdm4bhp"/><path class="sgz4g8k3l"/><path class="ievtq1brs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:row-count-check-outline-regular" /></template>
<style>
.ievtq1brs {
  d: path("M14.5 17.5 17 20l4.5 -4.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsy-y08mq {
  d: path("M3 4h14");
}

.sgz4g8k3l {
  d: path("M3 14h14");
}

.sixdm4bhp {
  d: path("M3 9h14");
}

</style>
