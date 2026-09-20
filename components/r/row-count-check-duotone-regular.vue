<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xoozo9b3t"/><path class="vk-tazw8e"/><path class="bq62evb_e"/><path class="vo3ao2o1l"/><path class="rsy-y08mq"/><path class="sixdm4bhp"/><path class="sgz4g8k3l"/><path class="ievtq1brs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:row-count-check-duotone-regular" /></template>
<style>
.bq62evb_e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

.vk-tazw8e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vo3ao2o1l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 17.5 17 20l4.5 -4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xoozo9b3t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
